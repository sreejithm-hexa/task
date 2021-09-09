node {
    environment {
        GRADLE_HOME="/opt/gradle/gradle-6.4.1"
        PATH = "/opt/gradle/gradle-6.4.1/bin"
    }
    stage('Build') {
        withEnv(["PATH+EXTRA=$PATH"])        
        sh "gradle build"
    }  
}
    
