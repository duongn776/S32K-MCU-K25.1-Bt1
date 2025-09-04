# So sánh kiến trúc CISC và RISC
---
### 1.1.  Giới thiệu khái niệm cơ bản về CISC (Complex Instruction Set Computer) và RISC (Reduced Instruction Set Computer)
- **CISC(Complex Instruction Set Computer)** là 1 kiến trúc máy tính với tập lệnh lớn và phức tạp, trong đó một lệnh có thể thực hiện nhiều thao tác (tải dữ liệu, tính toán, lưu kết quả).
Mục tiêu là giảm số lượng chương trình và giúp mã hóa rút gọn hơn, nhưng điều này cũng khiến thời gian thực thi có thể chậm hơn so với việc tăng tốc độ phức tạp
- **RISC(Reduced Instruction Set Computer)** là 1 kiến trúc máy tính với tập lệnh đơn giản và nhỏ gọn, mỗi lệnh chỉ thực thi 1 thao tác. Mục tiêu giảm khối lượng xử lý trên mỗi lệnh, từ đó tăng tốc độ và hiệu quả.Bộ xử lý RISC thường sử dụng kỹ thuật pipeline, chia lệnh thành nhiều giai đoạn để nhiều lệnh thực hiện đồng thời, giúp tăng hiệu suất và rút ngắn thời gian thực thi.
### 1.2.  Trình bày ưu điểm và nhược điểm của từng loại kiến trúc. 
**- CISC**:
**Ưu điểm**: 
Kích thước mã giảm
Tiết kiệm bộ nhớ
Có khả năng thực hiện các lệnh phức tạp
**Nhược điểm**:
Thực thi chậm hơn
Thiết kế phức tạp
Tiêu thụ điện năng cao
**- RISC**:
**Ưu điểm**: 
Tập lệnh đơn giản
Hỗ trợ pipeline hiệu quả
Tiêu thụ điện năng thấp
**Nhược điểm**:
Chương trình dài hơn
Khả năng thực hiện các lệnh phức tạp bị hạn chế
### 1.3.1. Cấu trúc tập lệnh
**CISC (Complex Instruction Set Computer)**:
Tập lệnh phức tạp, nhiều lệnh
Một lệnh có thể thực hiện nhiều thao tác (load, tính toán, store).
Độ dài lệnh thường không cố định
**RISC (Reduced Instruction Set Computer)**:
Tập lệnh đơn giản, ít lệnh
Mỗi lệnh thực hiện một thao tác cơ bản.
Độ dài lệnh thường cố định
### 1.3.2. Tốc độ xử lý
**CISC (Complex Instruction Set Computer)**:
Một lệnh có thể thực hiện nhiều việc, nhưng thường mất nhiều chu kỳ clock.
RISC:
Mỗi lệnh đơn giản, thường chỉ mất 1 chu kỳ clock để thực thi.
### 1.3.3. Kích thước chương trình
**CISC (Complex Instruction Set Computer)**:
Do có lệnh phức tạp → một chương trình cần ít lệnh hơn → kích thước chương trình nhỏ hơn.
**RISC (Reduced Instruction Set Computer)**:
Do lệnh đơn giản → cần nhiều lệnh hơn để làm cùng công việc → kích thước chương trình lớn hơn.
### 1.3.4. Độ phức tạp phần cứng
**CISC (Complex Instruction Set Computer)**:
Phần cứng phức tạp, tốn nhiều transistor, khó tối ưu pipeline
**RISC (Reduced Instruction Set Computer)**:
Phần cứng đơn giản, dễ tối ưu pipeline, tiết kiệm điện năng
### 1.3.5. Ứng dụng thực tế
**CISC (Complex Instruction Set Computer)**:
Ví dụ: Intel x86, AMD.
Dùng nhiều trong PC, laptop, server, nơi cần khả năng tương thích và tập lệnh phức tạp
**RISC (Reduced Instruction Set Computer)**:
Ví dụ: ARM, MIPS
Dùng nhiều trong thiết bị di động, nhúng, IoT, nơi cần hiệu suất cao, tiết kiệm năng lượng.
### 1.4. Nêu quan điểm cá nhân: Trong bối cảnh phát triển hệ thống nhúng hiện nay, kiến trúc nào phù hợp hơn? Vì sao? 
Trong bối cảnh phát triển hệ thống nhúng hiện nay, RISC (đặc biệt là ARM) phù hợp hơn so với CISC bởi vì:
Tiêu thụ điện năng thấp
Hiệu suất/chi phí tốt
Hệ sinh thái phong phú
Khả năng mở rộng
