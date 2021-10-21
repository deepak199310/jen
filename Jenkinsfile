node
{
stage("Cloning from Git")
{
git branch: 'main', url: 'git@github.com:deepak199310/jen.git'
}
stage("Run a Shell Script")
{
sh "chmod 755 abc.sh"
sh "./abc.sh"
}
}
