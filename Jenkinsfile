pipeline {
    agent any // 使用任意可用的Jenkins节点

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}