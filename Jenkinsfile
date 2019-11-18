node{
  stage('SCM checkout'){
                     
                  git 'https://github.com/supriyo13/First'
              }


           stage('Compile-Package'){

                      def mvnHome =  tool name: 'apache-maven-3.6.1', type: 'maven'

                     sh "${mvnHome}/bin/mvn package"          
           }


           }


