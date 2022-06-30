pipeline{
    agent any
    stages{
        stage("Download"){
            steps{
                sh "wget https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.18.8.tar.xz"
            }
        }
        stage("Unpack") {
            sh "tar xvf linux-5.18.8.tar.xz"
        }
    }
}