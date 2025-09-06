# Backend API

## Description
A simple Node.js + Express API with one endpoint `/sayHello` that returns a JSON message.

## Run Locally
```bash
npm install
npm start
```

Visit: [http://localhost/sayHello](http://localhost/sayHello)

## Deployment
Deployment is automated with GitHub Actions. It:
1. Connects to VM via SSH.
2. Deploys the code.
3. Runs the API on port 80.

## Test
```bash
curl http://<VM-IP>/sayHello
```
Expected output:
```json
{"message": "Hello User"}
```
