pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                // Clone your repo automatically by Jenkins, so this can be optional
                echo 'Starting pipeline...'
            }
        }
        stage('Build') {
            steps {
                echo 'Listing repo files:'
                bat 'dir /s *.java'
                echo 'webhook trigger retest'

                // Uncomment below if you have .java files in src folder and want to compile them
                // echo 'Compiling Java files...'
                // sh 'javac src/*.java'
            }
        }
    }
}
