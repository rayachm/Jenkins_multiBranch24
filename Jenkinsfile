node('master')

{

stage('ContinuousDownload_loans')
         {
    git 'https://github.com/rayachm/gitinit.git'
        }

stage('Continuousbuild_loans')
         {
   sh label: '', script: 'mvn package'
        }

}
