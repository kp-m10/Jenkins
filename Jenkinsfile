node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com','6ee239a3-d9c4-4bd5-9cc5-295f8ad50374') {
        def customImage = docker.build("kunal007/dockerwebapp-1")
        customImage.push()
    }
}
