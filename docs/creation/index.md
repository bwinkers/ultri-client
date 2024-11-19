# Creation Notes

Notes on how this project was created.

## Create a new Quasar app

```sh
nvm use 20
yarn create quasar
```

## Create trusted cert for localhost

```sh
mkdir ./src/certs
cd ./src/certs
mkcert localhost
```

Output:

```sh
Created a new certificate valid for the following names 📜
 - "localhost"

The certificate is at "./localhost.pem" and the key at "./localhost-key.pem" ✅

It will expire on 19 February 2027 🗓```
