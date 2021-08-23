node {
  git branch: 'main', url: 'https://github.com/SiwatINC/siwat-ubuntubaseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("siwatinc/siwat-ubuntubaseimage:focal",'focal').push()
  }
}
