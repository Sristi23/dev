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
    always {
        mail bcc: '', body: '''Hi Welcome to jenkins email alerts
        Thanks
        Srishti''', cc: '', from: '', replyTo: '', subject: 'Jenkins Job', to: 'sarawgisrishti5@gmail.com'
    }
   }
}
