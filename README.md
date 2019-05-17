# Kibana stem

Kibana analytics and search dashboard for Elasticsearch[\*](https://www.elastic.co/products/kibana)

## Build

Build from the official [kibana](https://hub.docker.com/_/kibana/) docker image. Stick to current version.

## Configuration

Configuration based on the official [sample config](https://github.com/elastic/kibana/blob/7.0/config/kibana.yml).

Changes made:

* `server.host` set to `0.0.0.0`
* `elasticsearch.hosts` set to default url of [Elasticsearch stem](https://github.com/withinstem/elasticsearch).

## Deployment

Deploy with docker using embedded [ops-docker](https://github.com/ops-tools/ops-docker) tool.

Exec `scripts/start` to launch local instance.

## License

[The Unlicense](LICENSE).
