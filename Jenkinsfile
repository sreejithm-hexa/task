node {
    stage('Clean') {
            sh "/opt/gradle/gradle-6.4.1/bin/gradle clean"
    }
    stage('Build') {
            sh "pwd"
            sh "/opt/gradle/gradle-6.4.1/bin/gradle build"
    }
    stage('Test') {
            sh "/opt/gradle/gradle-6.4.1/bin/gradle test"
    }
}

    
