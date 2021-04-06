// echo "----build start------"

// stage('Checkout Stage') {
//     echo "---Checkout---"
//     echo " 이제야 좀 되는거같네"
// }

// stage('Build Stage') {
//     echo "---Build Stage---"
// }

// stage('Push Stage') {
//     echo "---Push Stage---"
// }

node{
    stage('Checkout Stage'){
        print('chekout stage')
        sh 'docker build -t jenkins/please_dokcer .'
    }

    stage('Build Stage'){
        print('Build Stage')
    }

    stage('CPush Stage'){
        print('---Push Stage---')
    }
}