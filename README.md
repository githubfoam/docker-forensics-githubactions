# docker-forensics-githubactions
[![container modification  CI workflow](https://github.com/githubfoam/docker-forensics-githubactions/actions/workflows/container-changes-wf.yml/badge.svg?branch=main)](https://github.com/githubfoam/docker-forensics-githubactions/actions/workflows/container-changes-wf.yml)  
~~~
A tool for exploring each layer in a docker image
https://github.com/wagoodman/dive
Random Access Read-Only Tar Mount 
https://github.com/mxmlnkn/ratarmount
~~~
~~~
Component evidence

File system
copy-on-write diffs inside /var/lib/docker

Memory
gcore 
obdump
[memfetch](https://github.com/citypw/lcamtuf-memfetch
gdb
dd

Shared volumes

microservices

Containers in a forensic environment
containers may be paused at any time
containers may be quarantined by removing network access or system call privileges

Container isolation
Network isolation
Process namespacing
File system chroot
Device access control
Default seccomp profile
~~~