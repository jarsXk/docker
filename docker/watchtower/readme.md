## run once
```
docker run \
   --name=watchtower \
   -v /var/run/docker.sock:/var/run/docker.sock \
   containrrr/watchtower \
   --run-once \
   --cleanup
```