```
docker run -d --rm --name slow -v ${PWD}/squid.conf:/etc/squid/squid.local.conf -p 10001:10001 -p 10002:10002 -p 10003:10003 minimum2scp/squid
```

```
curl -i -x http://localhost:10002 http://example.com
```
