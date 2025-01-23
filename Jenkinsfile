pipeline {
    agent any
    
    stages {
        stage('Parallel Execution') {
            parallel {
                stage('Task 1') {
                    steps {
                        echo 'Executing Task 1'
                        script {
                            // Simulate a task with a sleep command
                            sleep(4)
                            echo 'Task 1 Completed with Output: Result from Task 1'
                        }
                    }
                }
                stage('Task 2') {
                    steps {
                        echo 'Executing Task 2'
                        script {
                            // Simulate another task with a sleep command
                            sleep(6)
                            echo 'Task 2 Completed with Output: Result from Task 2'
                        }
                    }
                }
                stage('Task 3') {
                    steps {
                        echo 'Executing Task 3'
                        script {
                            // Simulate a different task with a sleep command
                            sleep(5)
                            echo 'Task 3 Completed with Output: Result from Task 3'
                        }
                    }
                }
            }
        }
    }
}
