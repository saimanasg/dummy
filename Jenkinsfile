pipeline{
    agent any
    //environment{
        
       // def jname="${jsonPackager.name}"
        //def jversion="${jsonPackager.version}"
   // }
    
    stages{
       
        stage('Print Environment variables'){
            steps{
                script{
                def jsonPackager = readJSON file: "package.json" 
                echo "${jsonPackager.name}" 
                echo "${jsonPackager.version}"
                }
        }
        
      
    }
}
}
