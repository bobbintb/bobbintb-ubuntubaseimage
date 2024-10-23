node {
  git branch: 'main', url: 'https://github.com/bobbintb/bobbintb-ubuntubaseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("bobbintb/bobbintb-ubuntubaseimage:latest",'noble --no-cache').push()
  }
}
