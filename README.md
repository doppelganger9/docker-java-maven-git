# docker-java-maven-git

Docker image to build Java apps using Git, Maven, and of course Java. See [Dockerfile](Dockerfile) for details.

I was using [maven:3.5.2-jdk-8-alpine](https://github.com/andreptb/Dockerfiles/tree/master/maven/alpine/jdk-8) but it did not have git inside, so I just ended up pushing my own Docker image to fill this gap.

## Building

    docker build -f Dockerfile -t doppelganger9/java-maven-git:alpine-jdk-8-maven-3.5.2-git-latest .

## License

MIT
