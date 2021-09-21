node {
  git branch: 'main', url: 'https://github.com/SiwatINC/siwat-ubuntubaseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("siwatinc/siwat-ubuntubaseimage:latest").push()
      docker.build("siwatinc/siwat-ubuntubaseimage:focal",'focal').push()
      docker.build("siwatinc/siwat-ubuntubaseimage:hirsute",'hirsute').push()
      docker.build("siwatinc/siwat-ubuntubaseimage:focal-cuda",'focal-cuda').push()
  }
}
