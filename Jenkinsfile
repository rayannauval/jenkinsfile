
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
                            echo 'rahasia1: '+rahasia1
                            echo 'rahasia2: '+rahasia2
                        }

                    }
                }
            }
        }
        