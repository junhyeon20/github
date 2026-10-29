# github

```bash
echo "# github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/junhyeon20/github.git
git push -u origin main
```

```bash
git pull                    # 1. 최신 내용 받기
# ... 코드 작업 ...
git status                  # 2. 뭐가 바뀌었는지 확인
git add .                   # 3. 스테이징
git commit -m "작업 내용"   # 4. 커밋
git push                    # 5. 올리기
```