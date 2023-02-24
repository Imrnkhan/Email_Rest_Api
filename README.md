# Email_Rest_Api


### Build Rest API for MasaiMail Application

- User should be able to send and receive mails
- User should able to send a mail to many persons at once
- User should able to star & delete mails
- User should able to Register to Masaimail App
- User should able to login to Masaimail App




User should have following fields-

![image](https://user-images.githubusercontent.com/95843558/221269583-340e2146-a1ac-4165-a0de-d99653b3d48b.png)

### Rest API for User Resource

![image](https://user-images.githubusercontent.com/95843558/221269611-a5483cd7-567b-4bf0-81d3-595c4d9ff0e3.png)

### Rest API for Email Resource

![image](https://user-images.githubusercontent.com/95843558/221269639-6494b965-9fd0-4c5e-a8df-4452571d426f.png)

### Task - 1

- Build Rest API for Email, User
- Use MySQL database
- Use Response Entity depending upon the output.

### Task - 2

- Identify the Relationship between the User and Email and Implement that Relationship
- Use DTO wherever required
- Complete the All User and Email APIs

### Task - 3

- Implement Exceptional Handling in the project
    - Handle Custom Exception
    - Create Custom Error Structure Response for Client
    - Create Global Exception Handler to handle the exceptions globally: All other exception handled in this single place
- Swagger Rest API Documentation
- Add Validations
    - First Name must not contain numbers or special characters
    - Last Name must not contain numbers or special characters
    - Mobile number must have 10 digits
    - Password should be alphanumeric and must contain 6-12 characters having at least one special character, one upper case, one lowercase, and one digit.
    - date of birth should not be in future
