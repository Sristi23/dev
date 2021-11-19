def notificationEmails="sarawgisrishti5@gmail.com"
pipeline{

   agent any
  stages {
    stage("build")
    {
       steps
      {
         echo 'build file'
      }
    }
    
    stage("test")
    {
      steps
      {
        echo 'test file'
      }
    }
  }
post
   {
      success
      {
         mail bcc: '',body: "${notificationEmails}"
      }
   }
}
