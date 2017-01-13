node {
	stage 'Checkout'
		checkout scm
	
    stage('Build') { // <2>
        /* .. snip .. */
    }
    stage('Test') {
        /* .. snip .. */
    }
	
    input 'Do you approve deployment?'
    stage('Deploy') {
        /* .. snip .. */
    }
}
