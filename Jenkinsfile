node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com','docker_hub') {
        def suctomImage = docker.build("kunal007/dockerwebapp")
        custommage.push()
    }
}
