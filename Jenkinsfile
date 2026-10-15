
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
                                ),
                                string(
                                    credentialsId: 'secret2',
                                    variable:'rahasia2'
                                )
                            ]
                        ){
                            echo 'rahasia1: '+rahasia1;
                        }

                    }
                }
            }
        }
        