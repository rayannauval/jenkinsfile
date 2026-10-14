
        pipeline {
            agent {
                node {
                    label "l1 && l2"
                }
            }
            stages {
                stage("jenkinsfile.stage1"){
                    steps{
                        echo 'jenkinsfile.step1'
                    }
                }
            }
        }
        