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
 
                 sh 'mvn package'            }


           }



      }

  }
