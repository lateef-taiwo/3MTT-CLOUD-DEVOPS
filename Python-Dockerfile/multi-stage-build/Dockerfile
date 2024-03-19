# Multi-stage Dockerfile

# stage 1: BUild stage
FROM python:3.11-alpine3.19 as build
WORKDIR /app
COPY . .

# Stage 2: Runtime
FROM python:3.11-alpine as runtime
WORKDIR /app
COPY --from=build /app /app
CMD [ "python", "app.py" ]