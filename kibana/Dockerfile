# Use a minimal base image from Elastic's official repositories
FROM docker.elastic.co/kibana/kibana-oss:7.1.1

# The image is pre-configured to run Kibana and depends on Elasticsearch being available.
# This file is minimal as it leverages the pre-built, optimized official image.

# Optional: Add a healthcheck instruction
HEALTHCHECK CMD curl --fail http://localhost:5601 || exit 1

