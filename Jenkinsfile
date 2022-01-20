node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("jayant3787/jayant_demo")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}