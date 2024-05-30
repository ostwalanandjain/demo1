pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Scan') {
            steps {
                echo 'Scanning the code..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo """Deploying....
                
                The Declarative Pipeline example above contains the minimum necessary structure to 
                implement a continuous delivery pipeline. The agent directive, which is required, instructs Jenkins to allocate an executor and workspace 
                for the Pipeline. Without an agent directive, not only is the Declarative Pipeline not valid, it would not be capable of doing any work!
                By default the agent directive ensures that the source repository is checked out and made available for steps in the subsequent stages.
                
                """
            }
        }
    }
}
