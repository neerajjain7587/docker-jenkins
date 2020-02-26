node {
    def customImage = docker.build("my-image","-f ${dockerfile} ./dockerfiles")
    customImage.push()
}
