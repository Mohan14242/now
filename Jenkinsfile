pipeline {
    agent any

    parameters {
        string(name: 'person', defaultValue: 'mr mohan', description: 'Who should I say hello to')
        text(name: 'biography', defaultValue: '', description: 'Enter information about you')
        booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
        choice(name: 'CHOICE', choices: ['one', 'two', 'three'], description: 'Pick someone')
        password(name: 'password', defaultValue: 'secret', description: 'Please enter the password')
    }

    stages {
        stage('Example') {
            steps {
                // Your pipeline steps go here
                echo "Hello, ${params.person}!"
                echo "Biography: ${params.biography}"
                echo "Toggle Value: ${params.TOGGLE}"
                echo "Choice: ${params.CHOICE}"
                // Passwords are not printed for security reasons
            }
        }
    }
}
