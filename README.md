# Static Website DevOps Project

This is a beginner DevOps project where I:
- Made a simple HTML website 
- Put it inside a Docker container 
- Used GitHub Actions  to build it automatically on push

## 🔧 Tools Used
- HTML
- Docker
- GitHub Actions
- NGINX

##  How to Run Locally
```bash
docker build -t my-static-site .
docker run -p 8080:80 my-static-site
