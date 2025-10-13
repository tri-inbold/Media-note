# Media QC v22.2

Đây là một ứng dụng web mạnh mẽ được thiết kế để kiểm tra chất lượng (QC) các tệp video, hình ảnh và GIF. Nó cung cấp một không gian làm việc tương tác nơi người dùng có thể tải lên nhiều loại tệp đa phương tiện, xem lại chúng một cách đồng bộ và thêm các chú thích chi tiết.

https://tri-inbold.github.io/Media-note/


## Các tính năng chính

*   **Không gian làm việc linh hoạt:** Kéo và thả các tệp đa phương tiện (video, hình ảnh, GIF) trực tiếp vào không gian làm việc. Người dùng có thể di chuyển, thay đổi kích thước và sắp xếp các "artboard" chứa nội dung đa phương tiện một cách tự do.
*   **Hỗ trợ đa định dạng:**
    *   **Video:** Tải và phát các định dạng video phổ biến.
    *   **Hình ảnh:** Hiển thị các định dạng ảnh tĩnh.
    *   **GIF:** Chuyển đổi và phát các tệp GIF dưới dạng video lặp lại.
*   **Chú thích nâng cao:**
    *   **Nhiều công cụ vẽ:** Thêm nhận xét, vẽ hình chữ nhật, hình tròn, đường thẳng và mũi tên trực tiếp lên video và hình ảnh.
    *   **Chú thích hình ảnh:** Dán hoặc tải lên hình ảnh để làm chú thích.
    *   **Màu sắc tùy chỉnh:** Chọn từ một bảng màu hoặc sử dụng bộ chọn màu để có màu chú thích cụ thể.
*   **Dòng thời gian (Timeline) đồng bộ:**
    *   **Điều khiển chính:** Một dòng thời gian tổng thể cho phép phát, tạm dừng, tua và điều khiển tốc độ phát lại của tất cả các video cùng một lúc.
    *   **Đồng bộ hóa:** Giữ cho tất cả các video được phát đồng bộ với nhau.
    *   **Điều khiển riêng lẻ:** Mỗi video cũng có các điều khiển phát lại và âm lượng riêng.
*   **Quản lý nhận xét hiệu quả:**
    *   **Danh sách nhận xét:** Tất cả các chú thích được liệt kê trong một bảng điều khiển bên phải, được nhóm theo từng tệp đa phương tiện.
    *   **Dấu thời gian:** Các nhận xét trên video được tự động gắn dấu thời gian, cho phép người dùng chuyển đến khung hình chính xác.
    *   **Tìm kiếm và lọc:** Dễ dàng tìm kiếm các nhận xét cụ thể.
*   **Công cụ OCR (Nhận dạng ký tự quang học):**
    *   Trích xuất văn bản trực tiếp từ hình ảnh hoặc khung hình video bằng cách chọn một vùng.
*   **Lưu và xuất:**
    *   **Lưu dưới dạng HTML:** Lưu toàn bộ phiên làm việc, bao gồm các tệp đa phương tiện đã tải lên, chú thích và bố cục không gian làm việc vào một tệp HTML duy nhất.
    *   **Đóng gói dự án:** Xuất toàn bộ dự án dưới dạng tệp .zip, bao gồm tệp HTML và các tệp đa phương tiện liên quan.

## Cách sử dụng

1.  **Mở `index.html`:** Khởi chạy ứng dụng bằng cách mở tệp `index.html` trong trình duyệt web của bạn.
2.  **Tải lên tệp:**
    *   Kéo và thả các tệp video, hình ảnh hoặc GIF vào cửa sổ ứng dụng.
    *   Hoặc, nhấp đúp vào vùng trống để mở hộp thoại chọn tệp.
3.  **Sắp xếp không gian làm việc:**
    *   Nhấp và kéo tiêu đề của mỗi artboard để di chuyển nó.
    *   Kéo góc dưới cùng bên phải của artboard để thay đổi kích thước.
4.  **Thêm chú thích:**
    *   Chọn một công cụ từ thanh công cụ (ví dụ: nhận xét, hình chữ nhật).
    *   Nhấp và kéo trên artboard để tạo chú thích.
    *   Nhập văn bản cho nhận xét của bạn vào danh sách ở bảng điều khiển bên phải.
5.  **Điều khiển phát lại:**
    *   Sử dụng các điều khiển trên dòng thời gian chính để quản lý tất cả các video.
    *   Sử dụng các điều khiển riêng lẻ trên mỗi artboard video để điều khiển cụ thể.
6.  **Lưu công việc của bạn:**
    *   Nhấp vào nút "Save HTML File" để lưu trạng thái hiện tại của bạn. Thao tác này sẽ tạo ra một tệp HTML mới chứa tất cả dữ liệu của bạn.

## Các phím tắt

Ứng dụng hỗ trợ một loạt các phím tắt để tăng tốc quy trình làm việc của bạn. Nhấp vào nút **?** trong ứng dụng để xem danh sách đầy đủ. Một số phím tắt phổ biến bao gồm:

*   **V:** Công cụ chọn
*   **H:** Công cụ kéo (Pan)
*   **Q, W, E, R, T, Y, U:** Chọn các công cụ vẽ, hình ảnh và OCR
*   **Phím cách:** Phát/Tạm dừng video đã chọn
*   **Ctrl + Phím cách:** Phát/Tạm dừng tất cả video
*   **Ctrl + S:** Lưu tệp
*   **Ctrl + D:** Mở/Thêm tệp
*   **← / →:** Chuyển đến khung hình trước/tiếp theo

## Các thư viện được sử dụng

*   **Tesseract.js:** Cho chức năng OCR.
*   **JSZip:** Để đóng gói các dự án thành tệp .zip.
*   **gifler.js:** Để xử lý và hiển thị các tệp GIF.
