pipeline {
  agent any
  stages {
    stage('Inicializar / Mensagem') {
      steps {
        echo 'Iniciando a pipeline!!!'
        mail(subject: '{Jenkins] Iniciando pipeline', body: 'Estamos iniciando a pipeline', to: 'edvaldooliveira@alu.ufc.br')
      }
    }

  }
}