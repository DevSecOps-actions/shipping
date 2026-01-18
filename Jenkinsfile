@Library('jenkins-shared-library') _

def configmap = [
    project: "roboshop",
    component: "shipping"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    javaEKSpipeline(configmap)
}
else{
    echo "Please follow the CR(change release) process"
}
