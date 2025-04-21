# Use official Node.js image with Python
FROM node:18 AS dev_container_auto_added_stage_label

# Install Python
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    ln -s /usr/bin/python3 /usr/bin/python && \
    apt-get clean

# Create working directory
WORKDIR /workspace

# Set default shell (optional)
CMD [ "bash" ]
