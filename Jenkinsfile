node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("1612599/simpleWeb")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}