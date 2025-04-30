# 🤖 personal_chatbot_ez

Xây dựng chatbot AI thông minh sử dụng **Gradio UI** kết hợp **dữ liệu cá nhân riêng tư** và **tìm kiếm Internet**, phù hợp cho cá nhân, doanh nghiệp, hoặc bất kỳ ai muốn ứng dụng AI vào thực tế.

---

## 📽️ Video hướng dẫn đầy đủ: [Build Chatbot AI Với Dữ Liệu Cá Nhân - Dùng LangChain + Gradio | Full Tutorial 2025](https://youtu.be/r88d9YR49Us)

> Trong video này, bạn sẽ học cách:
- Thiết lập giao diện chatbot bằng **Gradio**
- Kết nối chatbot với **Private Docs** (tài liệu cá nhân như .txt, .pdf…)
- Tích hợp chức năng **tìm kiếm Internet** để bổ sung dữ liệu realtime
- Tối ưu chatbot cho **mục đích kinh doanh** hoặc **cá nhân hóa**

🎥 Playlist liên quan: [Tự Động Ghi Biên Bản Cuộc Họp với AI](https://www.youtube.com/playlist?list=PLt11NO3k9FFyDDmVF_ssNgZ-zwiOt6eh8)

---

## 📁 Cấu trúc thư mục

| File | Mô tả |
|------|-------|
| `Chatbot_ez.ipynb` | Notebook chính để chạy chatbot |
| `CHÍNH SÁCH BẢO MẬT.txt` | Ví dụ tài liệu riêng tư (Private Docs) |
| `DANH SÁCH NGÀY NGHỈ TRONG NĂM.txt` | File dữ liệu cá nhân (dùng để truy xuất) |
| `NỘI QUY LAO ĐỘNG CÔNG TY X.txt` | Tài liệu mẫu gắn vào chatbot |
| `README.md` | Tệp hướng dẫn repo (bạn đang đọc nó) |

---

## 🚀 Yêu cầu hệ thống

- Python 3.8+
- API key cho OpenAI
- API tavily
---

## ⚙️ Cách chạy nhanh

```bash
git clone https://github.com/ShynBui/personal_chatbot_ez.git
cd personal_chatbot_ez
jupyter notebook Chatbot_ez.ipynb
