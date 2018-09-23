# Push a datapoint using Curl

`curl 'https://warp10.gra1.metrics.ovh.net/api/v0/update' -H 'X-Warp10-Token: READ_TOKEN' -d '// metric.name{context=metricContext} 100' -vvvv`{{execute}}
