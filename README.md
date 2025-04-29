# Disk Scheduling Algorithms Visualization

Đây là ứng dụng web mô phỏng các thuật toán lập lịch đĩa (Disk Scheduling Algorithms) sử dụng React và TypeScript.

## Tính năng

- Nhập vị trí bắt đầu, số track, danh sách request và chọn thuật toán.
- Hỗ trợ các thuật toán: FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK.
- Hiển thị trực quan đường đi của đầu đọc đĩa và tổng quãng đường di chuyển.

## Cài đặt & chạy

1. Cài đặt dependencies:
   ```sh
   npm install
   ```

2. Chạy ứng dụng:
   ```sh
   npm run dev
   ```

3. Mở trình duyệt và truy cập [http://localhost:5173](http://localhost:5173)

## Cấu trúc thư mục

- `src/components`: Các component giao diện
- `src/logic/algorithms`: Các thuật toán lập lịch đĩa
- `src/pages`: Trang chính của ứng dụng
- `src/styles`: File CSS
