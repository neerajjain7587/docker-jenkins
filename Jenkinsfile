node {
    checkout scm
    def customImage = docker.build("my-image","-f ${Dockerfile} ./dockerfiles")
    customImage.push()
}
