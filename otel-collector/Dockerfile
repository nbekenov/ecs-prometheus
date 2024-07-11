FROM public.ecr.aws/aws-observability/aws-otel-collector:v0.39.1
COPY config.yaml /etc/ecs/otel-config.yaml
CMD ["--config=/etc/ecs/otel-config.yaml"]