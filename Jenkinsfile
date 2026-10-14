
        pipeline {
            stages {
                stage("jenkinsfile.stage1"){
                    steps{
                        echo 'jenkinsfile.step1.1'
                        echo 'jenkinsfile.step1.2'
                    }
                }

                stage("jenkinsfile.stage2"){
                    steps{
                        echo 'jenkinsfile.step2.1'
                        echo 'jenkinsfile.step2.2'
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
        