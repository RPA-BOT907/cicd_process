pipeline {
    agent any
    
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                bat 'cd "C:\\Program Files\\Blue Prism Limited\\Blue Prism Automate"'
                bat 'set path="C:\\Users\\haris\\Downloads\\BPA Process - pro.bpprocess"'
                bat 'set username="admin"'
                bat 'set password="Sarasu@10"'
                bat 'AutomateC.exe /importrelease %path% /user %username% %password% /dbconname jenkins'
                bat 'AutomateC.exe /publish "Pro" /user %username% %password%'
                bat 'echo completed successfully'
            }
        }
    }


                }

