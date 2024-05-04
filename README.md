# Langchain
data_source : Thư mục dùng để lưu trữ các tài liệu phục vụ cho việc xây dựng hệ cơ sở dữ liệu vector.
data_source/generative_ai/download.py: File code dùng để tải tự động một số các bài báo khoa học dưới dạng file pdf.
src/base/llm_model: File code dùng để khai báo hàm khởi tạo mô hình ngôn ngữ lớn.

src/rag/: Thư mục dùng để lưu trữ các code liên quan đến xây dựng RAG, bao gồm:
(a) src/rag/file_loader.py: File code dùng để khai báo các hàm load file pdf (vì tài liệu
của chúng ta thu thập thuộc file pdf).
(b) src/rag/main.py: File code dùng để khai báo hàm khởi tạo chains.
(c) src/rag/offline_rag.py: File code dùng để khai báo PromptTemplate.
(d) src/rag/utils.py: File code dùng để khai báo hàm tách câu trả lời từ model.
(e) src/rag/vectorstore.py: File code dùng để khai báo hàm khởi tạo hệ cơ sở dữ liệu vector.
src/app.py: File code dùng để khởi tạo API.