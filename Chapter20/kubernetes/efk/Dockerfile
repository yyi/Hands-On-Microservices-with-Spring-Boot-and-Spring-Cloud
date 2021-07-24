FROM fluent/fluentd-kubernetes-daemonset:v1.13.2-debian-elasticsearch7-1.0

RUN gem install fluent-plugin-detect-exceptions -v 0.0.13 \
 && gem sources --clear-all \
 && rm -rf /var/lib/apt/lists/* \
           /home/fluent/.gem/ruby/2.3.0/cache/*.gem
