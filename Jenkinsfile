node{
    stage('Test'){
      properties([parameters([booleanParam(defaultValue: true, description: 'true', name: 'truth'), string(defaultValue: 'akhil', description: 'your name', name: 'name', trim: false)])])
   }
    stage('test print'){
        if ${truth}
        echo "HEy It is truth not dare Mr.${name}"
}
