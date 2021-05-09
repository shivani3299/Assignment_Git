pipeline {
    agent any
    parameters{
        string(name:'Name', defaultValue:'Shivani')
        choice(name:'number', choices:['1','2','3','4'] )
    
    }
    stages {
        stage('Build') {
            steps {
                echo 'build'
                echo '%Name%'
                echo '%number%'
            }
        }
    }
}
