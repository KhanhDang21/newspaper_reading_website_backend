# crawl-data-miniproj

BackEnd được xây dựng với FastAPI 

- Cài đặt và chạy dự án:
1. Tạo virtual environment và cài đặt thư viện
- python -m venv .venv
- .venv\Scripts\activate trên Windows
- pip install -r requirements.txt

2. Khởi chạy server 
- uvicorn app.main:app --reload
- -> Truy cập API documents tại: http://localhost:8000/docs

- Chạy bằng Docker:
- docker-compose up --build

