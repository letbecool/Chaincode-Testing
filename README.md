# Chaincode-Testing
Chaincode testing step by step 
1. open setup Directory and run the setup_test.go 
    Setup_test.go simplly checks your enviroment is set or not. If this runs successfully then you can start for the chaincode test. To ensure, this is working you can see like following output from the test result on terminal. 
    
                Running tool: /usr/bin/go test -timeout 30s -run ^TestSetup$

                Cool! successfully setup the test Enviroment : You see Testing information as below : 
                PASS
                ok  	_/home/gopal/testingsession/chaincodetest/Chaincode-Testing/setup	0.002s

    Note: path above shown will be your own path istead of  " _/home/gopal/testingsession/chaincodetest/ " 

2. Testing chaincode using MuckStub 
    
