node {
    stage ('Clonar repositorio'){
        git 'https://github.com/EliAlarcon/app-web2-backend.git'
    }
    
    stage('Limpiar'){
        bat 'mvn clean'
    }
    
    stage('Compilar'){
        bat 'mvn package'
    }
}