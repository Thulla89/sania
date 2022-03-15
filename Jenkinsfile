 pipeline
{
    agent any
    stages
    {
        stage('creation of file')
    {
        steps
        {
            sh 'touch /root/vijay.txt'
        }
     }
         stage('port checking ')
    {
        steps
        {
            sh 'netstat -plunt'
        }
     }
         stage('cpu')
    {
        steps
        {
            sh 'top -h'
        }
     }
     
     stage('creating one more file')
    {
        steps
        {
            sh 'mkdir /root/example'
        }
     }
     
    }
}
