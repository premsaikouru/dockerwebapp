node {
    checkout scm 
    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {
        def customImage = docker.build("premsaikouru/dockerwebapp")
        
        customImage.push()
    }    

}
