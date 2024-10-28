pipeline{
agent any
stages{
	stage("Build_Stage"){
		steps{
			echo "Building stage....."
		     }
	}
	stage("Test_Stage"){
		steps{
			echo "Testing stage....."
		     }
	}
	stage("Deploy_Stage"){
		steps{
			echo "Deploying stage....."
		     }
	}
}
	post
	{
	always
		{
			echo "Thank you...!"
		}
	}
}

