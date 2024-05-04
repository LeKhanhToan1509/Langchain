# Dự Án Langchain

![text](https://images.seeklogo.com/logo-png/52/1/langchain-logo-png_seeklogo-528369.png)

## Hướng Dẫn Chạy Dự Án

## Cấu Trúc Dự Án

### Thư Mục `data_source`

Thư mục này chứa các tài liệu được sử dụng để xây dựng cơ sở dữ liệu vector.

-   **data_source/generative_ai/download.py**
    -   Script này được dùng để tự động tải các bài báo khoa học dưới dạng file PDF.

### Thư Mục `src/base`

-   **llm_model.py**
    -   File này chứa hàm khởi tạo mô hình ngôn ngữ lớn (LLM).

### Thư Mục `src/rag`

Thư mục này chứa các mã nguồn liên quan đến việc xây dựng Retrieval-Augmented Generation (RAG).

-   **file_loader.py**
    -   File này chứa các hàm để tải các file PDF (vì tài liệu thu thập là file PDF).
-   **main.py**
    -   File này chứa hàm khởi tạo chains.
-   **offline_rag.py**
    -   File này chứa khai báo cho PromptTemplate.
-   **utils.py**
    -   File này chứa hàm tách câu trả lời từ model.
-   **vectorstore.py**
    -   File này chứa hàm khởi tạo hệ cơ sở dữ liệu vector.

### Thư Mục `src`

-   **app.py**
    -   File này chứa mã khởi tạo API.

## Lưu Ý

-   Đảm bảo cài đặt mọi phụ thuộc và thực thi các script trong môi trường phù hợp để tránh các lỗi không mong muốn.
