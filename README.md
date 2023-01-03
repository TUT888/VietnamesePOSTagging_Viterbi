# Gán nhãn từ loại cho tiếng Việt (Vietnamese Part of Speech Tagging)
Đồ án giữa kỳ môn "Xử lý ngôn ngữ tự nhiên" <br>
Xây dựng chương trình gán nhãn từ loại cho tiếng Việt <br>

## Project Description

Đồ án bao gồm các phần:
1. Xây dựng chương trình gán nhãn từ loại bằng thuật toán Viterbi
- Xây dựng chương trình và đánh giá độ chính xác
- Gán nhãn từ loại cho câu khi nhập vào một câu tiếng Việt
2. Sử dụng thư viện gán nhãn từ loại có sẵn để so sánh kết quả

## Installation
- Dự án có sử dụng thư viện `underthesea` phiên bản `1.1.5` để tách từ tiếng Việt (word_tokenize) và gán nhãn từ loại (pos_tag) <br>
- Chi tiết thư viện tại: https://underthesea.readthedocs.io/en/latest/readme.html <br>

## Files in repository
- vietnamese_pos_tagging.ipynb: file Jupyter Notebook của dự án
- vi_train.pos: file dữ liệu để huấn luyện
- vi_test.pos: file dữ liệu để kiểm tra và đánh giá
