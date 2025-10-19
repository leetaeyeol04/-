# ① 새 저장소 복제 (GitHub 리포지토리 연결)
git clone https://github.com/yourname/AI-Routine-Assistant.git
cd AI-Routine-Assistant

# ② 새 파일 생성 (src/main.py)
echo 'print("AI 루틴 어시스턴트: 생활 데이터 기반 컨디션 예측 시스템")' > src/main.py

# ③ 변경사항 추가 (stage 상태로 올리기)
git add src/main.py

# ④ 커밋 (변경사항을 기록)
git commit -m "main.py 파일 추가 및 첫 코드 작성"

# ⑤ 원격 저장소로 푸시 (GitHub에 반영)
git push

