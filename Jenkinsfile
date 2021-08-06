node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("nssuresh21/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
