# 🤖 Trợ lý phân loại Cảm xúc Tiếng Việt (Tên Project)

Đây là project môn **Seminar chuyên đề** dùng Streamlit để demo mô hình AI phân loại cảm xúc cho văn bản tiếng Việt. 

![img.png](img.png)

-----

## 🚀 Chức năng chính

  * Phân loại văn bản đầu vào thành 3 nhãn: **POSITIVE** (Tích cực), **NEGATIVE** (Tiêu cực), và **NEUTRAL** (Trung tính).
  * **Tiền xử lý thông minh:** Tự động sửa các từ viết tắt (vd: "ko bt" -\> "không biết") và **khôi phục dấu tiếng Việt** (vd: "hang dep" -\> "hàng đẹp") trước khi phân tích.
  * **Lưu lịch sử:** Hiển thị 50 kết quả phân loại gần nhất trong thanh sidebar.
  * Giao diện đơn giản, dễ sử dụng.

-----

## 🛠️ Công nghệ sử dụng

  * **Ngôn ngữ:** Python
  * **Giao diện (Frontend):** Streamlit
  * **Mô hình AI (Models):**
      * **Sentiment Analysis:** `wonrax/phobert-base-vietnamese-sentiment` (từ Hugging Face)
      * **Diacritic Restoration (Khôi phục dấu):** `bmd1905/vietnamese-correction` (từ Hugging Face)
  * **Thư viện:** `transformers`, `sqlite3`
  * **Database:** SQLite (để lưu lịch sử)

-----

## 📂 Cách chạy project

1. **Cài đặt các thư viện cần thiết:**
   
    ```bash
    pip install -r requirements.txt
    ```

2. **Chạy ứng dụng Streamlit:**

    ```bash
    streamlit run frontend.py
    ```

3. Mở trình duyệt lên và truy cập vào `http://localhost:8501`.

-----

## 🧑‍💻 Tác giả

  * **Họ và tên:** Phạm Tấn Khương
  * **MSSV:** 3122410191
  * **Họ và tên:** Đặng Huỳnh Minh Thái
  * **MSSV:** 31214101448

-----

## Lưu ý
Vì không muốn bị sao chép code, nên mã nguồn của dự án trong link github này không thể tải về được.
Thây cô hoặc bạn nào có nhu cầu muốn tải và xem code của em. Vui lòng liên hệ email sau: tankhuongpham35@gmail.com.

-----
