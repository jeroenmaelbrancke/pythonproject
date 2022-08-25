pipeline {
    agent { 
        docker { 
            image 'python:latest'
            args '-u root --entrypoint='
        }
    }

    stages {
        stage("Run unittest") {
            steps {
                sh "python3 -m unittest test_volume_cuboid.py"
            }
        }
    }
}
