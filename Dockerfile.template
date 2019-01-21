FROM centos:7
RUN yum install httpd ; yum clean all ; mkdir /build
COPY $CI_PROJECT_DIR/container-files /build
ENTRYPOINT /build/hello.sh
