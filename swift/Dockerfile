# syntax=docker/dockerfile:1
# Status: Beta
# GA updates: https://github.com/awsdocs/aws-doc-sdk-examples/issues/4132
FROM swift:5.4.3
RUN mkdir /src
COPY . /src/
WORKDIR /src/swift/example_code/s3/basics
RUN swift build
CMD ["bash"]