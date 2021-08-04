pipeline {
    agent any

    stages {
        stage("Run unittest") {
            steps {
                sh "python3 -m unittest test_volume_cuboid.py"
            }
        }
    }
}
