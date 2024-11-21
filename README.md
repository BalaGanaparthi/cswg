# cswg

git tag -a v1.0.0 -m "Version 1.0.0"
git push origin v1.0.0
git log --pretty=format:%s <last release>...HEAD --no-merges
git tag -a <tag name> -m"$(git log --pretty=format:%s <last release>...HEAD --no-merges)"
git add .
git commit -m "Add: QFC Images"
git push -u origin main
git tag -a v0.1.38 -m "Add: Reset password prompt"
git push origin v0.1.38
