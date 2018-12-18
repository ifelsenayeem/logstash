# Logstash

Logstash is an open source, server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite “stash.” (Ours is Elasticsearch). Logstash has over 200 plugins, and you can write your own very easily as well.

You can find the documentation and getting started guides for Logstash on the [elastic.co](https://www.elastic.co/guide/en/logstash/current/getting-started-with-logstash.html) site.

## Run
```
sudo /usr/share/logstash/bin/logstash -f coping_index.conf --path.settings /etc/logstash --debug
```
