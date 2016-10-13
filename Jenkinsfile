node ('linux'){
  stage 'Build and Test'
  env.PATH = "${env.PATH}"
  git url: "https://github.com/khudgins/hello.git"
  sh 'ruby test.rb'
 }
