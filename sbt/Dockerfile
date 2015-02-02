FROM guersam/java:oracle-8

RUN \
  echo "deb http://dl.bintray.com/sbt/debian /" | tee -a /etc/apt/sources.list.d/sbt.list && \
  apt-get update && \
  apt-get install -y --force-yes sbt && \
  rm -rf /var/lib/apt/lists/* && \
  rm -rf /var/cache/sbt

