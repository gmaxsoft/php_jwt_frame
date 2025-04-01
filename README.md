# PHP JWT LOGIN AUTH 

A simple example of logging in using JWT token. 
A JSON Web Token (JWT) is a compact, self-contained way to securely transmit information between parties, often used for authentication and authorization in web applications, APIs, and distributed systems.

## :star: Give A Star

You can also give this repository a star to show more people and they can use this repository.

# ℹ️ How to use this Repository?

1. Clone the repository to your local machine

```bash
  git clone https://github.com/gmaxsoft/php_jwt_frame.git

```
2. Navigate to the project directory

```bash
  cd php_jwt_frame
```
3. Install the necessary dependencies
```bash
  composer install
```

4. Configure .env file

Generate SECRET_KEY 

A secret key is required when creating a JWT, is unique and should be kept private. This is encoded in the token to ensure that the token is more difficult to replicate. Keep in mind that a token can be easily and maliciously duplicated if someone else has access to this key

To generate the key you can use openssl command:
openssl rand -hex 32
