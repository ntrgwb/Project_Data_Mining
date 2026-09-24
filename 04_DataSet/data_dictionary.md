# Data Dictionary - ViSpamReviews Dataset

| Tên trường | Kiểu dữ liệu | Miền giá trị | Missing | Ý nghĩa nghiệp vụ |
| :--- | :--- | :--- | :--- | :--- |
| Rating | int64 | 1 - 5 | 0 | Điểm đánh giá sao sản phẩm |
| Comment | object | Text | 0 | Nội dung văn bản đánh giá |
| Label | int64 | 0, 1 | 0 | 0: Thật (Non-spam), 1: Spam |
| SpamLabel | int64 | 0, 1, 2, 3 | 0 | 0: Thật, 1: Mẫu sẵn, 2: Lạc đề, 3: Ký tự rác |