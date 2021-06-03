pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh './term2/ultra-large-scale/mine/compile.sh'
            }
        }

        stage('Publish') {
            steps {
                sh 'cp term2/ultra-large-scale/mine/thesis.pdf /opt/tomcat/webapps/ROOT'
            }
        }
    }
}
