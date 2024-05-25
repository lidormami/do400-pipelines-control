node ('nodejs'){
  stage ('checkout'){
    git branch: 'main', url: 'git@github.com:lidormami/do400-pipelines-control.git'
}
  stage ('backend test'){
    sh 'node ./backend/test.js'
}
stage ('frontend test'){
    sh 'node ./frontend/test.js'
}
}
