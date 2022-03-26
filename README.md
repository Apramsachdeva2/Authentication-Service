# Authentication-Service
REST API that provides endpoint to validate the user using username and password.

url :- http://apram-auth-service.herokuapp.com/authservice/auth

It accepts and object of ApplicationUser and extracts username and password from that objects and validates both username and password with the datat present in AuthenticationDB.

If the username and password matches with the entry in database, it send the status 'OK' else sends status as 'NOT_FOUND'

