node {
	stage 'Checkout'
		checkout scm
	
    stage('Build') { // <2>
        /* .. snip .. */
    }
    stage('Test') {
        /* .. snip .. */
    }
	
    stage('Deploy') {
	    input 'Do you approve deployment?'
        /* .. snip .. */
    }
}
