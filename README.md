# serenityjs-docker

After pulling the resources, please run the following commands:

1.) docker run --rm -ti -v /dev/shm:/dev/shm --privileged marktigno/serenityjs-docker bash

2.) Inside the running container, execute: "./run-serenity"

3.) To export the test results to the host file system, on a separate terminal/cmd execute: "docker cp marktigno/serenityjs-docker:/app/serenityjs-docker/target ."

This is my repo to build and run serenity-js on docker.
Credits to @jan-molak
