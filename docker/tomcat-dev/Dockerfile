FROM centos:centos7.7.1908

ADD ./files/openjdk-11+28_linux-x64_bin.tar.gz /opt/
ENV PATH /opt/jdk-11/bin:$PATH
ENV JAVA_HOME /opt/jdk-11

ADD ./files/apache-maven-3.6.3-bin.tar.gz /opt/
ENV PATH /opt/apache-maven-3.6.3/bin:$PATH