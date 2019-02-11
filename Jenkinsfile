node{
    stage('Test'){
      properties([parameters([booleanParam(defaultValue: true, description: 'true', name: 'truth'), string(defaultValue: 'akhil', description: 'your name', name: 'name', trim: false)])])
   }
    stage('test print'){
 
        echo "HEy It is truth not dare Mr ${params.name}" 
}
}
