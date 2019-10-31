<!--

********************************************************************************

WARNING:

    DO NOT EDIT "julia/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "julia/" combined with a set of templates)

********************************************************************************

-->

# Supported tags and respective `Dockerfile` links

(See ["What's the difference between 'Shared' and 'Simple' tags?" in the FAQ](https://github.com/docker-library/faq#whats-the-difference-between-shared-and-simple-tags).)

## Simple Tags

-	[`1.3.0-rc4-buster`, `1.3.0-buster`, `1.3-buster`, `1.3-rc-buster`](https://github.com/docker-library/julia/blob/b4e9903f90adf5d14655fe9c4bfa75d9db945b4d/1.3-rc/buster/Dockerfile)
-	[`1.3.0-rc4-stretch`, `1.3.0-stretch`, `1.3-stretch`, `1.3-rc-stretch`](https://github.com/docker-library/julia/blob/b4e9903f90adf5d14655fe9c4bfa75d9db945b4d/1.3-rc/stretch/Dockerfile)
-	[`1.2.0-buster`, `1.2-buster`, `1-buster`, `buster`](https://github.com/docker-library/julia/blob/5f637f20522f82f953c69318002820da70d2e3f9/1.2/buster/Dockerfile)
-	[`1.2.0-stretch`, `1.2-stretch`, `1-stretch`, `stretch`](https://github.com/docker-library/julia/blob/db1a7e6fad976b52043021c7c4716dba6a2ab03b/1.2/stretch/Dockerfile)
-	[`1.0.5-buster`, `1.0-buster`](https://github.com/docker-library/julia/blob/4c770401df0b946da5cf61150bedb05280b218a6/1.0/buster/Dockerfile)
-	[`1.0.5-stretch`, `1.0-stretch`](https://github.com/docker-library/julia/blob/4c770401df0b946da5cf61150bedb05280b218a6/1.0/stretch/Dockerfile)

## Shared Tags

-	`1.3.0-rc4`, `1.3.0`, `1.3`, `1.3-rc`:
	-	[`1.3.0-rc4-buster`](https://github.com/docker-library/julia/blob/b4e9903f90adf5d14655fe9c4bfa75d9db945b4d/1.3-rc/buster/Dockerfile)
-	`1.2.0`, `1.2`, `1`, `latest`:
	-	[`1.2.0-buster`](https://github.com/docker-library/julia/blob/5f637f20522f82f953c69318002820da70d2e3f9/1.2/buster/Dockerfile)
-	`1.0.5`, `1.0`:
	-	[`1.0.5-buster`](https://github.com/docker-library/julia/blob/4c770401df0b946da5cf61150bedb05280b218a6/1.0/buster/Dockerfile)

[![i386/julia build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/i386/job/julia.svg?label=i386/julia%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/i386/job/julia/)

# Quick reference

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

-	**Where to file issues**:  
	[https://github.com/docker-library/julia/issues](https://github.com/docker-library/julia/issues)

-	**Maintained by**:  
	[the Docker Community](https://github.com/docker-library/julia)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/julia/), [`arm32v7`](https://hub.docker.com/r/arm32v7/julia/), [`arm64v8`](https://hub.docker.com/r/arm64v8/julia/), [`i386`](https://hub.docker.com/r/i386/julia/), [`windows-amd64`](https://hub.docker.com/r/winamd64/julia/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/julia/` directory](https://github.com/docker-library/repo-info/blob/master/repos/julia) ([history](https://github.com/docker-library/repo-info/commits/master/repos/julia))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images PRs with label `library/julia`](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fjulia)  
	[official-images repo's `library/julia` file](https://github.com/docker-library/official-images/blob/master/library/julia) ([history](https://github.com/docker-library/official-images/commits/master/library/julia))

-	**Source of this description**:  
	[docs repo's `julia/` directory](https://github.com/docker-library/docs/tree/master/julia) ([history](https://github.com/docker-library/docs/commits/master/julia))

# What is Julia?

Julia is a high-level, high-performance dynamic programming language for technical computing, with syntax that is familiar to users of other technical computing environments. It provides a sophisticated compiler, distributed parallel execution, numerical accuracy, and an extensive mathematical function library.

> [julialang.org](http://julialang.org/)

![logo](https://raw.githubusercontent.com/docker-library/docs/520519ad7db3ea9fd5d3590e836c839a0ffd6f19/julia/logo.png)

# How to use this image

## Start Julia REPL

Starting the Julia REPL is as easy as the following:

```console
$ docker run -it --rm i386/julia
```

## Run Julia script from your local directory inside container

```console
$ docker run -it --rm -v "$PWD":/usr/myapp -w /usr/myapp i386/julia julia script.jl arg1 arg2
```

# License

View [license information](http://julialang.org/) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `julia/` directory](https://github.com/docker-library/repo-info/tree/master/repos/julia).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
