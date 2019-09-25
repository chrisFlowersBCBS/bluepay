# bluepay

Payment service that will be used to get payment profiles based on parameters

Example: 
In local, *https://localhost:8080/paymentprofileId* should return the paymentprofile object which contains uuid, last name, first name, phone, email.

**DockerMakeFile** will be used to make sure the environment is the same for everyone that needs to work on it.

Docker will also be used for the database, will use profiles to set up the dev enviornment and the prod enviornment.

