node {
  git branch: 'main', url: 'https://github.com/SiwatINC/siwat-ubuntubaseimage'
  docker.withRegistry("https://ghcr.io/v2") {
      docker.build("siwatinc/siwat-ubuntubaseimage:latest",'hirsute --no-cache').push()
      docker.build("siwatinc/siwat-ubuntubaseimage:focal",'focal --no-cache').push()
      docker.build("siwatinc/siwat-ubuntubaseimage:hirsute",'hirsute --no-cache').push()
      docker.build("siwatinc/siwat-ubuntubaseimage:focal-cuda",'focal-cuda --no-cache').push()
  }
}
