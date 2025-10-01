# Media note

Công cụ QC video và hình ảnh, hoạt động hoàn toàn trên trình duyệt. Tất cả chức năng, giao diện và dữ liệu chú thích đều được gói gọn trong một file HTML duy nhất.

https://tri-inbold.github.io/Media-note/

https://tri-inbold.github.io/Media-note/beta


## Tính năng nổi bật

*   **Hai chế độ trong một:** Tự động chuyển đổi giao diện và chức năng phù hợp khi bạn làm việc với video (`Video Mode`) hoặc chỉ với hình ảnh (`Image Mode`).
*   **Chú thích đa dạng:** Thêm bình luận, vẽ các hình dạng (vuông, tròn, đường thẳng, mũi tên) trực tiếp lên media.
*   **Hệ thống trả lời lồng nhau:** Dễ dàng thảo luận và theo dõi các chuỗi phản hồi.
*   **Lưu trữ tất cả trong một file:** Toàn bộ chú thích, hình ảnh dán vào và thông tin media được nhúng trực tiếp vào file `.html`. Chỉ cần gửi một file duy nhất cho người khác để xem lại.
*   **Không cần cài đặt:** Hoạt động hoàn toàn offline trên mọi trình duyệt hiện đại (Chrome, Firefox, Edge).
*   **Giao diện Sáng/Tối:** Tự động chuyển đổi theo hệ thống hoặc cho phép người dùng tùy chỉnh.
*   **Hỗ trợ đa người dùng:** Lưu lại tên người dùng để dễ dàng xác định ai đã tạo chú thích.

## Cách sử dụng

1.  **Tải file:** Tải về file `index.html`.
2.  **Mở trên trình duyệt:** Mở file vừa tải bằng trình duyệt web của bạn (khuyên dùng Chrome).
3.  **Kéo và thả:** Kéo và thả file video hoặc hình ảnh của bạn vào cửa sổ trình duyệt để bắt đầu.
    *   Nếu có **video**, ứng dụng sẽ vào `Video Mode`.
    *   Nếu chỉ có **hình ảnh**, ứng dụng sẽ vào `Image Mode`.
4.  **Lưu lại:** Sử dụng phím tắt `Ctrl + S` hoặc nút "Lưu file HTML" để lưu lại toàn bộ công việc của bạn.

## Phím tắt chính

#### Chung (Cả hai chế độ)

| Phím tắt             | Chức năng                               |
| -------------------- | --------------------------------------- |
| `Ctrl` + `D`         | Mở file / Thêm hình ảnh mới (Image Mode) |
| `Ctrl` + `S`         | Lưu lại file HTML                       |
| `Ctrl` + `Shift` + `S` | Lưu thành một file mới                  |
| `Ctrl` + `C` / `V`   | Copy / Dán chú thích, hình ảnh          |
| `Delete`             | Xóa các mục đã chọn                     |
| `Q, W, E, R, T`      | Chọn nhanh các công cụ vẽ               |

#### Video Mode

| Phím tắt             | Chức năng             |
| -------------------- | --------------------- |
| `Spacebar`           | Play / Pause          |
| `←` / `→`            | Di chuyển từng frame   |
| `Shift` + `←` / `→`  | Di chuyển từng giây   |
| `Lăn chuột`          | Tiến/lùi các frame    |

#### Image Mode

| Phím tắt               | Chức năng                  |
| ---------------------- | -------------------------- |
| `Spacebar` + Kéo chuột | Di chuyển (Pan)            |
| `Chuột giữa`           | Di chuyển (Pan)            |
| `Ctrl` + Lăn chuột    | Phóng to / Thu nhỏ        |
| `Ctrl` + `G`           | Tự động sắp xếp các hình ảnh |

## Công nghệ sử dụng

Dự án được xây dựng hoàn toàn bằng "Vanilla Stack" để đảm bảo tính gọn nhẹ và di động:

*   HTML5 (Canvas API)
*   CSS3 (Flexbox, Grid)
*   JavaScript (ES6+)

Không sử dụng bất kỳ framework hay thư viện bên ngoài nào.

## Contact

tri.vu.trong@inbold.com
