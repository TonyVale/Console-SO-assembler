# TPE-ARQUI-2025-2Q

docker run -d -v ${PWD}:/root --security-opt seccomp:unconfined -it --name TPE  agodio/itba-so:2.0

docker start TPE

docker exec -ti TPE bash

./run.sh
