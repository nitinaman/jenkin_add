pipeline {
    agent any
    stages {
        stage('Calculate Sum') {
            steps {
                script {
                    // Define two numbers
                    def num1 = 10
                    def num2 = 25
                    
                    // Calculate the sum
                    def sum = num1 + num2
                    
                    // Print the result to the console output
                    echo "The first number is: ${num1}"
                    echo "The second number is: ${num2}"
                    echo "The sum of ${num1} and ${num2} is: ${sum}"
                }
            }
        }
    }
}
