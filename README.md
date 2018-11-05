Use this docker image if you need jupyter python notebooks with the CERN ROOT library. Built from rootproject/root-fedora image. Both python and ROOT C++ kernels are available.

Run with e.g.

`docker run -p 3000:8080 pedwink/pyroot-notebook`

and then access through localhost:3000 in your browser.
The Dockerfile lives here: https://github.com/sidebo/docker-pyroot-notebook
