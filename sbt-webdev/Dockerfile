FROM guersam/sbt:1.0

RUN \
  apt-get update && \
  apt-get install -y ruby1.9.3 ruby-dev make && \
  rm -rf /var/lib/apt-lists/* && \
  rm -rf /var/cache/*

RUN \
  gem install sass -v 3.4 && \
  gem install compass -v '~> 1.0.1'
