def gitUrl = 'https://github.com/RingierIMU/mob-android-test'
def branchName = 'master'

pipeline {
  agent {
    label 'master'
  }
  stages {
    // stage('checkout'){
    //     steps {
    //         checkout scm: [$class: 'GitSCM', branches: [[name: "*/${branchName}"]], userRemoteConfigs: [[url: "${gitUrl}"]]]
    //     }
    // }
    stage('log variables'){
        steps {
            echo branchName
            echo gitUrl
        }
    }
    // stage('clean') {
    //     steps {
    //         sh './gradlew clean'
    //     }
    // }
    // stage('build') {
    //     steps {
    //         sh './gradlew :app:assembleDebug'
    //     }
    // }
    // stage('publish-app-center') {
    //     steps {
    //         appCenter apiToken: '9fa1293a6804d8eba491e0a844666c26ddfb2f3d',
    //                 ownerName: 'mobile-team-opo3',
    //                 appName: 'Jenkins-Test',
    //                 pathToApp: 'app/build/outputs/apk/debug/app-debug.apk',
    //                 distributionGroups: 'Testers'
    //     }
    // }      
  }
}
