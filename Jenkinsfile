node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', '08a7a160-603c-4bc8-a000-6093b3931667') {

        def customImage = docker.build("7989461575/ajaytest .")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
