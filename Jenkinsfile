pipeline { 
      agent {
	      label {
		      label '172.31.36.46_slave3'
		      
	      }
	  }
	  stages {
	         stage ('slave3') {
			   steps {
			 sh "sudo yum install git -y"
		     sh "sudo yum install httpd -y"
			 sh "sudo service httpd start"
			 sh "sudo cp -r index.html /var/www/html/"
			 sh "sudo chmod -R 777 /var/www/html/index.html"
			 
			   }
			 }
			 
	  }

}
