# Intro to DevOps Lab
# Intro to DevOps

Set up a DevOps toolchain, containerised a Node.js app with Docker, automated builds with a Makefile, and tagged a v1.0.0 release.

## Commands Covered

```bash
git init
git add .
git commit -m "feat: add Makefile automation"
docker build -t my-app:1.0 .
docker run -p 3000:3000 my-app:1.0
git tag -a v1.0.0 -m "First epic DevOps lab release!"
git push origin v1.0.0
```
