pipeline{
    agent any
    environment{
        def jsonPackager = readJSON file: "package.json" 
        def jname="${jsonPackager.name}"
        def jversion="${jsonPackager.version}"
    }
    
    stages{
       
        stage('Print Environment variables'){
            steps{
                echo "${janme}" 
                echo "${jversion}"
        }
        
      
    }
}
}
