


# BÀI 5: CHUẨN HÓA QUY TRÌNH BÁO CÁO SỰ CỐ AN NINH MẠNG

## Phần 1. Phân tích :
* **Cơ chế hoạt động:** AutoFilter đóng vai trò như công cụ tìm kiếm nhanh trên Excel, cho phép lọc chính xác các dòng dữ liệu (mã độc, mức độ rủi ro, mốc thời gian) mà không làm thay đổi hay mất dữ liệu gốc.
* **Ứng dụng:** Giúp kỹ sư an ninh mạng bóc tách các dòng log quan trọng từ hàng nghìn dòng dữ liệu thô để đưa vào báo cáo NetGuard.

## Phần 2. Triển khai:
- **`BaoCao_NetGuard.xlsx`**: File Excel dùng `=VLOOKUP(TRIM(...))`.
        
    -   **`BaoCao_NetGuard.docx`**: File Word có thiết kế **Auto TOC** (mục lục tự động).
        
    -   **`BaoCao_NetGuard.pptx`**: Slide PowerPoint dùng font **Inter** hoặc **Montserrat** (không dùng Times New Roman).
       
