// to login
docker login bharathpersonal7898
// to build
docker build . -t firstnode2244
// to run
docker run -p 49160:3000 -d firstnode
// to go inside cmd
docker exec -it d7629a08004cc3276545998e1f39fd8629112fc58e608c8943268890a63358b0 /bin/bash
// to see logs
docker logs d7629a08004cc3276545998e1f39fd8629112fc58e608c8943268890a63358b0
// to see containers
docker ps -a
// to stop
docker stop d7629a08004c
// to see images
docker images
// to push
docker push bharathpersonal7898/firstnode2244
