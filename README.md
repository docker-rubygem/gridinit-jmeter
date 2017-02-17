[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/gridinit-jmeter.svg)](https://hub.docker.com/r/rubygem/gridinit-jmeter/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/gridinit-jmeter.svg)](https://hub.docker.com/r/rubygem/gridinit-jmeter/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/gridinit-jmeter.svg)](https://hub.docker.com/r/rubygem/gridinit-jmeter/)
[![Gem Downloads](https://img.shields.io/gem/dt/gridinit-jmeter.svg)](https://rubygems.org/gems/gridinit-jmeter/)
# gridinit-jmeter

Auto-Generated Docker image for gridinit-jmeter to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/gridinit-jmeter`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/gridinit-jmeter`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/gridinit-jmeter`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/gridinit-jmeter/)
