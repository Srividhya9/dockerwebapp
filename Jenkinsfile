node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'ambati2019') {

        def customImage = docker.build("ambati2019/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
