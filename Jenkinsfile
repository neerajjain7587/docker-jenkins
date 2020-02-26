node {
    def customImage = docker.build("my-image:${env.BUILD_ID}", "-f ${dockerfile} ./")
    customImage.push()
}
