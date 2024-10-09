# 베이스 이미지는 Python 3.9
FROM python:3.9-slim

# 작업 디렉토리 설정
WORKDIR /app

# requirements.txt 파일 복사 및 의존성 설치
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

# Flask 앱 소스 복사
COPY . .

# Flask 서버 실행
CMD ["python", "app.py"]
