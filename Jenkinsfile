
        pipeline {
            agent any
            stages {
                stage("stage1"){
                    steps{
                        echo 'step1.1'
                        echo 'step1.2'
                    }
                }

                stage("stage2"){
                    steps{
                        echo 'step2.1'
                        sh 'cat gagal.txt'
                        echo 'step2.2'
                    }
                }

                stage("stage3"){
                    steps{
                        echo 'step3.1'
                        echo 'step3.2'
                    }
                }
            }

            post {
                always {
                    echo 'pesan: always'
                }
                success {
                    echo 'pesan: success'
                }
                failure {
                    echo 'pesan: failure'
                }
                cleanup {
                    echo 'pesan: cleanup'
                }
            }
        }
        