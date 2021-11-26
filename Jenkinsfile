pipeline{
    agent any
    environment{
        def jsonPackager = readJSON file: "package.json" 
    }
    
    stages{
       
        stage('Print Environment variables'){
            steps{
                echo "${jsonPackager.version}" 
                echo "${jsonPackager.name}"
        }
        
      
    }
}
}
