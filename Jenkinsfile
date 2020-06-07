node('ansible')
{
    stage('scm')
    {
       git 'https://github.com/sujith140/ansiblepractice.git'
    }
    stage('execute playbook')
    {
        sh 'ansible-playbook -i lampfinal/hosts lampfinal/lamp.yaml'
    }
}

