FROM amazonlinux
RUN yum -y install tcsh
RUN yum -y install java-1.8.0-openjdk.x86_64
RUN curl https://bintray.com/sbt/rpm/rpm | tee /etc/yum.repos.d/bintray-sbt-rpm.repo
RUN yum -y install sbt
RUN yum -y install pico
