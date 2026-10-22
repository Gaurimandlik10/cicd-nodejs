# CI/CD with GitHub Actions: Node.js + Docker Hub
## Run locally
```bash
npm install
npm test
npm start                      # http://localhost:3000
docker build -t cicd-nodejs-demo .
docker run -p 3000:3000 cicd-nodejs-demo
```
