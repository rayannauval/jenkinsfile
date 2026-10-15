
        pipeline {
            agent any
            stages {
                stage("stage1"){
                    steps{
                        withCredentials(
                            [
                                string(
                                    credentialsId: 'secret1',
                                    variable:'rahasia1'
                                )
                            ]
                        ){
                            sh 'echo $rahasia1'
                        }

                    }
                }
            }
        }
        