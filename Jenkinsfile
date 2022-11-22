node('master')

{

stage('ContinuousDownload_master')
         {
    git 'https://github.com/rayachm/gitinit.git'
        }

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }

}
