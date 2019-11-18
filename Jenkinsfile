pipeline{
     agent any


       stages{

           stage('SCM checkout'){


                steps{ 
                     
                 
                     git 'https://github.com/supriyo13/First'
              }


             }



           stage('Compile-Package'){


                steps{ 
                      def mvnHome =  tool name: 'apache-maven-3.6.1', type: 'maven'

                     sh "${mvn package}/bin/mvn package"            }


           }



      }

  }
