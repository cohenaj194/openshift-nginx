# openshift-nginx

```
docker build -t cohenaj194/openshift-nginx .
# openshift containers cant run on port 80 for security reasons
docker run --rm -d -p 80:8081 cohenaj194/openshift-nginx
```
Testing out https://github.com/torstenwalter/openshift-nginx dockerfiles 
