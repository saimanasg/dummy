pipeline{
    agent any
    environment{
        def jsonPackager = readJSON file: "package.json" 
    }
    
    stages{
       
        stage('Print Environment variables'){
            steps{
                echo "${jasonPackager.version}" 
                echo "${jasonPackager.name}"
        }
        
      
    }
}
}
