pipeline { 
      agent {
	      label {
		      label 'built-in'
	      }
	  }
	  stages {
	         stage ('master') {
			   steps {
			 sh "yum install git -y"
		     sh "yum install httpd -y"
			 sh "service httpd start"
			 sh "cp -r /mnt/assignment/index.html /var/www/html/"
			 sh "chmod -R 777 /var/www/html/index.html"
			 
			   }
			 }
			 
	  }

}

