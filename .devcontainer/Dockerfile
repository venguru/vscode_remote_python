FROM python:3.8

WORKDIR /workspace

RUN apt-get update
RUN apt-get install -y vim

# Clean up
RUN apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*