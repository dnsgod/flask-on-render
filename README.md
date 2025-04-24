# 🐍 Flask API with Render 배포

간단한 Flask API를 개발하고, Render를 활용해 클라우드에 배포한 프로젝트입니다.

## 🔗 배포 주소
👉 [https://flask-on-render.onrender.com](https://flask-on-render.onrender.com)

## ✅ 기능
- `/` 경로로 접근 시 "Flask API 성공!" 메시지 반환
- gunicorn을 통한 WSGI 서버 구동
- Render 무료 계정을 활용한 배포 자동화

## 🛠️ 사용 기술
- Python 3.10+
- Flask 2.2.5
- Gunicorn 21.2.0
- Render (무료 클라우드 호스팅)

## 📁 폴더 구조
flask-on-render/ ├── app.py # Flask 앱 메인 파일 ├── requirements.txt # 패키지 목록 └── runtime.txt

🧠 회고
gunicorn 미포함으로 배포 실패 → 디버깅 후 requirements에 추가

Render 자동 빌드 시스템 이해

Flask API → 실전 배포 경험 체득 완료

📌 업로드 방법:
```bash
touch README.md
# 위 내용 붙여넣기
git add README.md
git commit -m "Add README for Render deployment"
git push origin main
