node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("2imfatx/20127589:1.1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
