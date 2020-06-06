node('ansible')
{
    stage('scm')
    {
       git 'https://github.com/sujith140/ansiblepractice.git'
    }
    stage('execute playbook')
    {
        sh 'ansible-playbook -i lampwithgroupandhostvars/hosts lamp_with_Variables/lamp.yaml'
    }
}

