@Library('jenkins-shared-library')_

def configMap = [
    project: "expense",
    component: "backend"
]

if (! env.BRANCH_NAME.equalsIgnoreCase('main')){
    nodeJSEKSPipline(configMap)
}
else{
    echo "please follow production process"
}     