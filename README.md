# ansible-elasticsearch

An Ansible role for installing [Elasticsearch](https://www.elastic.co/products/elasticsearch).

## Role Variables

- `elasticsearch_version` - Elasticsearch version to install
- `elasticsearch_short_version` - Elasticsearch short version
- `elasticsearch_cluster_name` - Elasticsearch cluster name (default: `elasticsearch`)
- `elasticsearch_data_dir` - Elasticsearch data directory (default: `/var/lib/elasticsearch`)
- `elasticsearch_bind_host` - Address Elasticsearch binds to (default: `127.0.0.1`)
- `elasticsearch_tcp_port` - TCP port Elasticsearch binds to (default: `9300`)
- `elasticsearch_http_port` - HTTP port Elasticsearch binds to (default: `9200`)
- `elasticsearch_cors_enable` - Toggle CORS support (default: `false`)
- `elasticsearch_cors_allow_origin` - Allow origin setting for CORS (default: `*`)

## Example Playbook

See the [examples](./examples/) directory.
