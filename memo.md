#깃허브 사용시에는 폴더 자체를 올릴 수는 없지만 파일을 따로 올려서 사용은 가능함
# 1. 작업 폴더로 이동
cd ~/Desktop/폴더 이름-----기기의 폴더의 주소

# 2. Git 저장소 초기화
git init

# 3. GitHub 원격 저장소 연결 (이미 연결된 경우 생략 가능)
git remote add origin https://github.com/사용자이름/저장소이름.git
# 예: https://github.com/yookdy/algorithm_sol.git

# 4. 전체 파일 Git에 추가
git add .

# 5. 커밋 (변경사항 기록)
git commit -m "Initial commit with all files"

# 6. 브랜치 이름을 main으로 설정 (선택사항)
git branch -M main

# 7. GitHub에 푸시 (업로드)
git push -u origin main



올린 폴더에 추가 내용이 들어갈 때
# 1. 변경된 파일 Git에 추가
git add .

# 2. 변경 내용을 커밋
git commit -m "Explain what changed"

# 3. GitHub에 푸시
git push
