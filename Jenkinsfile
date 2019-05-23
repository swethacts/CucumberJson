pipeline {
    agent any
    stages {
        stage('Import results to Xray') {
            steps {
             //  step([$class: 'XrayImportBuilder', endpointName: '/cucumber', importFilePath: './Cucumber2ScenariosJson.json', serverInstance: 'ecf1cd2e-826a-4259-bc88-1c561365820a'])
                  step([$class: 'XrayImportBuilder', endpointName: '/cucumber', importFilePath: './cucumber.json', serverInstance: 'ecf1cd2e-826a-4259-bc88-1c561365820a'])
            }
        }
    }
}
