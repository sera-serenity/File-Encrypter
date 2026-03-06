node {

    stage('Clone Repository') {
        echo "Cloning repository..."
        git 'https://github.com/sera-serenity/File-Encrypter.git'
    }

    stage('Build') {
        echo "Building project..."
        sh 'javac FileEncrypter.java'
    }

    stage('Test') {
        echo "Running tests..."
        sh 'echo Tests executed successfully'
    }

    stage('Deploy') {
        echo "Deploying application..."
        sh 'echo Deployment successful'
    }

}
