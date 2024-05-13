# how to remove everything from privategpt api

```
for i in `curl -X GET localhost:8001/v1/ingest/list| jq -r '.data[].doc_id'`; do curl -X DELETE loca
lhost:8001/v1/ingest/$i; done
```
