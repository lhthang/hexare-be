To solve cluster health: yellow issue

PUT /_settings
{
  "index" : {
        "number_of_replicas" : 0
    }
}

List all indexes
`localhost:9200/_cat/indices`

Check health
`localhost:9200/_cat/health`

List data in indexes
`http://localhost:9200/index_name/_search`
`http://localhost:9200/index_name/_search?q=string`

