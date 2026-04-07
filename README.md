# TravelBuddy AI Agent - Lab 4

Trợ lý ảo du lịch xây dựng trên LangGraph và OpenAI có khả năng suy luận đa bước.

## Thành phần dự án
- agent.py: Logic điều hướng LangGraph và luồng hội thoại.
- tools.py: Công cụ tra cứu (vé máy bay, khách sạn) và tính ngân sách.
- system_prompt.txt: Persona và các quy tắc (Rules/Constraints) cho Agent.
- test_results.md: Báo cáo kết quả chạy 5 kịch bản kiểm thử.
- explain.txt: Giải thích chi tiết logic Rules & Constraints.
- requirements.txt: Danh sách các thư viện Python cần thiết.
- .gitignore: Loại trừ venv và file .env bảo mật.

## Cách chạy ứng dụng
1. Cài đặt thư viện: `pip install -r requirements.txt`
2. Cấu hình file .env: `OPENAI_API_KEY=your_key`
3. Chạy chương trình: `python agent.py`
