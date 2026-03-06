node {

    stage('Clone Repository') {
        echo "Cloning repository..."
        git branch: 'main', url: 'https://github.com/sera-serenity/File-Encrypter.git'
    }

    stage('Build') {
        echo "Building Java project..."

        sh '''
        cd "Password Protection"
        mkdir -p build
        javac -d build src/*.java
        '''
    }

    stage('Test') {
        echo "Testing application..."

        sh '''
        cd "Password Protection"
        echo "Application compiled successfully"
        '''
    }

    stage('Deploy') {
        echo "Deploy stage completed (demo)"
    }

}
