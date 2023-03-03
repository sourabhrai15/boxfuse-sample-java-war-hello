node('built-in') {
    stage('download from git') {
        git changelog: false, credentialsId: '9add5e62-d3e9-471b-b0ce-9f386f53f032', poll: false, url: 'https://github.com/sourabhrai15/boxfuse-sample-java-war-hello.git'
}
stage('continuous build') {
sh 'mvn package'
}

 stage('continuous deployment') {
  sh 'echo "Deploy passed"'
}
}
