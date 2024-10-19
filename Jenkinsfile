pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', credentialsId: '1d4ded06-e47c-45a6-aae1-165eca7bfdec', url: 'https://github.com/moamjad0794/tweet-trend-new'
            }
        }
    }
}
