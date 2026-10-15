
        pipeline {
            agent any
            stages {
                stage("stage1"){
                    steps{
                        script {
                            def i = 2
                            if(i==3){
                                sh "echo 3"
                            }else if(i==2){
                                sh "echo 2"
                            }else{
                                sh "echo ELSE"
                            }
                        }
                    }
                }
            }
        }
        