node{
    stage('Test'){
      properties([parameters([booleanParam(description: 'true', name: 'truth'), string(defaultValue: 'akhil', description: 'your name', name: 'name', trim: false)])])
   }
    stage('test print'){
        if('${params.truth}'){
        echo "HEy It is truth not dare Mr ${params.name}" 
        }
        else{
            echo "dare"
        }
}
}
