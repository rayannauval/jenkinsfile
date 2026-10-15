
        pipeline {
            agent any
            stages {
                stage("stage1"){
                    steps{
                        script {
                            def i = 3
                            if(i==3){
                                sh "echo 3"
                            }elseif(i==2){
                                sh "echo 2"
                            }else{
                                sh "echo ELSE"
                            }
                        }
                    }
                }
            }
        }
        