# github-fastlane-app
A small  application with a GitHub Actions pipeline that tests, builds, and publishes  to GitHub Container Registry
# Running with Docker
```
//build it 
docker build -t github-fastlane-app:local

//run and deploy locally
docker run -d --name github-fastlane-app -p 8111:8111 github-fastlane-app:local

// pull the latest version 
docker pull ghcr.io/glyn-leigh/github-fastlane-app:latest

//deploy it on port 8111
docker run -d --name github-fastlane-app -p 8111:8111 ghcr.io/glyn-leigh/github-fastlane-app:latest
```
## Version Runs
<img width="833" height="98" alt="Screenshot 2026-09-16 111811" src="https://github.com/user-attachments/assets/4506aa8c-e2db-417f-a8ca-1a3242dd75f2" />
<img width="835" height="179" alt="Screenshot 2026-09-16 112717" src="https://github.com/user-attachments/assets/5aad967c-f87f-4fcc-9cfb-aadc9254742a" />
