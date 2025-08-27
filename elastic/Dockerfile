# Use a minimal base image from Elastic's official repositories
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:7.1.1

# The image is already configured to run Elasticsearch, so no further commands are needed.
# This file is minimal because it relies on the pre-built, optimized base image.
# We are simply pulling a specific, lightweight version of the official image.

# Optional: Add a healthcheck instruction to check the container's health
HEALTHCHECK CMD curl --fail http://localhost:9200 || exit 1

