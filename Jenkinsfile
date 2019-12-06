// Declarative //
pipeline {
agent any
stages {
stage('Example') {
steps {
echo 'Hello World'
}
}
}
post { ①
always { ②
echo 'I will always say Hello again!'
}
}
}
// Script //
