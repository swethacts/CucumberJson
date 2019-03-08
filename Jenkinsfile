pipeline {
    agent any
    stages {
        stage('Import results to Xray') {
            steps {
               step([$class: 'XrayImportBuilder', endpointName: '/cucumber', importFilePath: './Cucumber.json', serverInstance: 'ecf1cd2e-826a-4259-bc88-1c561365820a'])
            }
        }
    }
}
