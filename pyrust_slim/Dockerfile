FROM python:3.7-slim

RUN apt-get update && apt-get -y install curl

RUN curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain=nightly -y
ENV PATH="/root/.cargo/bin:$PATH"

RUN pip install pyo3-pack
