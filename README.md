# Authentication and Authorization API - Documentation

![youshallnotpass](https://github.com/juliocauan/authentication-server/assets/84354526/e4d27e22-8a5f-4d74-aacc-b95119852c10)

***
## 📖  Description

This is the documentation of a Rest API for user authentication and authorization. It limits user access to only what has been specifically assigned to them. <br/>
This API was developed as a personal challenge for learning different areas of development, which are:
 - Cybersecurity
 - Web development
 - CI/CD
 - Database Administrator
 - Security and Data Retention Policies
 - Token Management
 - Registration and Audit
 - Integration with Identity Systems

***
## 🛠️ Functionalities
**User Data Storage:**
   - Securely stores user data, including encrypted passwords and associated roles.

**User Authentication with JWT:**
   - Provides user authentication, generating JSON Web Tokens (JWT) upon successful login for secure access.

**"Forgot Password" Feature:**
   - Implements a secure "Forgot Password" functionality for users to reset their passwords.

**Admin Role Management:**
   - Enables administrators to update user roles for effective access control.

To see all endpoints descriptions, visit [Authentication API OpenAPI(Swagger) Documentation](https://app.swaggerhub.com/apis-docs/juliocauan/authentication/1.1.x)

***
## 🔮 Future implementations

1. Extra Security Policies
   - Strong Passwords
   - Account block after failed login attemps
   - Email verification upon user registration

2. Multifactor Authentication

3. Authentication via Google

***
## 📡 Used Technologies 
<div align="center">
  <img align="left" alt="OpenAPI (Swagger)" title="OpenAPI (Swagger)" height="30" width="30" src="https://avatars.githubusercontent.com/u/37325267?s=200&v=4">
</div>
<br/><br/>

***
## 🔎 Project Status

![Status Badge](https://img.shields.io/badge/status-development-green)
<br/>

To run this API locally on DEV mode, visit [Authentication API Server](https://github.com/juliocauan/authentication-server). <br/>
Obs: DEV mode will only mock emails, it won't send real ones. Production mode will be available shortly.

<br/>
