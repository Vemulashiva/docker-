<!--

********************************************************************************

WARNING:

    DO NOT EDIT "node/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "node/" combined with a set of templates)

********************************************************************************

-->

# Supported tags and respective `Dockerfile` links

**WARNING:** THIS IMAGE *IS NOT SUPPORTED* ON THE `arm32v5` ARCHITECTURE

[![arm32v5/node build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/node.svg?label=arm32v5/node%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/node/)

# Quick reference

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

-	**Where to file issues**:  
	[https://github.com/nodejs/docker-node/issues](https://github.com/nodejs/docker-node/issues)

-	**Maintained by**:  
	[The Node.js Docker Team](https://github.com/nodejs/docker-node)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/node/), [`arm32v6`](https://hub.docker.com/r/arm32v6/node/), [`arm32v7`](https://hub.docker.com/r/arm32v7/node/), [`arm64v8`](https://hub.docker.com/r/arm64v8/node/), [`i386`](https://hub.docker.com/r/i386/node/), [`ppc64le`](https://hub.docker.com/r/ppc64le/node/), [`s390x`](https://hub.docker.com/r/s390x/node/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/node/` directory](https://github.com/docker-library/repo-info/blob/master/repos/node) ([history](https://github.com/docker-library/repo-info/commits/master/repos/node))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images PRs with label `library/node`](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fnode)  
	[official-images repo's `library/node` file](https://github.com/docker-library/official-images/blob/master/library/node) ([history](https://github.com/docker-library/official-images/commits/master/library/node))

-	**Source of this description**:  
	[docs repo's `node/` directory](https://github.com/docker-library/docs/tree/master/node) ([history](https://github.com/docker-library/docs/commits/master/node))

# What is Node.js?

Node.js is a software platform for scalable server-side and networking applications. Node.js applications are written in JavaScript and can be run within the Node.js runtime on Mac OS X, Windows, and Linux without changes.

Node.js applications are designed to maximize throughput and efficiency, using non-blocking I/O and asynchronous events. Node.js applications run single-threaded, although Node.js uses multiple threads for file and network events. Node.js is commonly used for real-time applications due to its asynchronous nature.

Node.js internally uses the Google V8 JavaScript engine to execute code; a large percentage of the basic modules are written in JavaScript. Node.js contains a built-in, asynchronous I/O library for file, socket, and HTTP communication. The HTTP and socket support allows Node.js to act as a web server without additional software such as Apache.

> [wikipedia.org/wiki/Node.js](https://en.wikipedia.org/wiki/Node.js)

![logo](https://raw.githubusercontent.com/docker-library/docs/01c12653951b2fe592c1f93a13b4e289ada0e3a1/node/logo.png)

# How to use this image

See [How To Use This Image](https://github.com/nodejs/docker-node/blob/master/README.md#how-to-use-this-image) on GitHub for up-to-date documentation.

# License

View [license information](https://github.com/nodejs/node/blob/master/LICENSE) for Node.js or [license information](https://github.com/nodejs/docker-node/blob/master/LICENSE) for the Node.js Docker project.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `node/` directory](https://github.com/docker-library/repo-info/tree/master/repos/node).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
