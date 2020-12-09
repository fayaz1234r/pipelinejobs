#!groovy
  
node ("master"){
  
    stage('Checkout code') {
        echo "check out the code"
        }
    stage('Build') {
        echo "Building your package .."
        sh """
        cd $WORKSPACE
        ls -lrth
        """
     }
     
    stage('Upload Artifact to Nexus') {
        echo "Building your package .."
        }
}
