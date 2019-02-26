pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
		sh "container=\"\";flag=1;while [ ${flag} -lt 10 ]; do if [ -z ${container} ];then sleep 5;container=\"\"; flag=`expr $flag + 1`;else break;fi;done"
            }
        }
    }
}
