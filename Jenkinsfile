pipeline {
	agent any
		stages {
			stage('Clone') {
				steps {
					git branch: 'main'
						, url: 'https://github.com/your-username/your-
						repo.git'
				}
			}
			stage('Build') {
				steps {
					sh 'javac HelloWorld.java'
				}
			}
			stage('Deploy') {
				steps {
					sh 'java HelloWorld'
				}
			}
		}
}
