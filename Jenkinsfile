node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com','docker_hub') {
        def customImage = docker.build("kunal007/dockerwebapp")
        customImage.push()
    }
}
