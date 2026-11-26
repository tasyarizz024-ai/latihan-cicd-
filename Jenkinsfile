pipeline { 
agent any 
options { 
skipDefaultCheckout() 
} 
stages { 
stage('Checkout') { 
steps { 
checkout scm 
sh 'ls -la public' 
} 
} 
stage('Test') { 
steps { 
sh 'test -f public/index.html'
