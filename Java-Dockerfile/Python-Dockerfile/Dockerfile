FROM python:3.7
ARG AWS_ACCESS_KEY_ID
ARG AWS_SECRET_ACCESS_KEY
ARG AWS_DEFAULT_REGION
COPY . /app
WORKDIR /app
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN ./aws/install
RUN aws s3 cp --recursive s3://Demo_AWS/docker_s3_demo/ /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
