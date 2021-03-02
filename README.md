# docker-java-maven-git
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdoppelganger9%2Fdocker-java-maven-git.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdoppelganger9%2Fdocker-java-maven-git?ref=badge_shield)


Docker image to build Java apps using Git, Maven, and of course Java. See [Dockerfile](Dockerfile) for details.

I was using [maven:3.5.2-jdk-8-alpine](https://github.com/andreptb/Dockerfiles/tree/master/maven/alpine/jdk-8) but it did not have git inside, so I just ended up pushing my own Docker image to fill this gap.

## Building

    docker build -f Dockerfile -t doppelganger9/java-maven-git:alpine-jdk-8-maven-3.5.2-git-latest .

## License

MIT


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdoppelganger9%2Fdocker-java-maven-git.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdoppelganger9%2Fdocker-java-maven-git?ref=badge_large)