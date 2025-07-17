pipeline {
        agent worker
        stages {
                stage('Pipeline Stages'){
                        steps {
                                sh "ls -la"
                                sh "echo 'Hastalavista'"
                                echo "Creating a file..." > file.txt
                        }
                }
                stage('Another Stage'){
                steps {
                        sh "cat file.txt"
                        }
                }
        }
}
