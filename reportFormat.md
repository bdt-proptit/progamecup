# Mẫu Báo Cáo Kết Quả Bài Tập Code Game

## 1. Thông Tin Nhóm

**Tên Dự Án:** [Tên dự án]

**Link Dự Án:** [GitHub Link](#)

**Thành Viên Nhóm:**
- [Thành viên 1]
- [Thành viên 2]
- [Thành viên 3]
- [Thành viên 4]
- [Mentor]

## 2. Giới Thiệu Dự Án

**Mô tả:** [Dự án game làm cái gì]

## 3. Các Chức Năng Chính

- [Chức năng 1]
- [Chức năng 2]
- [Chức năng 3]
- [Chức năng 4]

## 4. Công Nghệ Sử Dụng

- [Công nghệ 1]
- [Công nghệ 2]
- [Công nghệ 3]
- [Công nghệ 4]

## 5. Ảnh và Video Demo

**Ảnh Demo:**
![Ảnh Demo](#)

**Video Demo:**
[Video Link](#)

## 6. Các Vấn Đề Gặp Phải

### Vấn Đề 1: [Mô tả vấn đề]
**Ví dụ:** Game gặp phải vấn đề hiệu năng kém, fps thấp dù không có nhiều đối tượng trên màn hình

### Hành Động Để Giải Quyết

**Giải pháp:** Do việc tạo object quá nhiều, nên dẫn tới tràn ram và giảm hiệu năng
- Sử dụng Design Pattern Object Pool để tái sử dụng object. Khi object không còn sử dụng, sẽ được đưa vào pool để sử dụng lại. 

### Kết Quả

- Sau khi sử dụng Object Pool, hiệu năng game đã được cải thiện, fps tăng lên đáng kể. Từ *30fps lên 60fps* (Rõ ràng hơn với số liệu cụ thể)

### Vấn Đề 2: [Mô tả vấn đề]
**Ví dụ:** Có quá nhiều class quái khác nhau, dù chúng có nhiều điểm chung


### Hành Động Để Giải Quyết

**Giải pháp:** Sử dụng Design Pattern Builder để tạo các object quái với các thuộc tính khác nhau mà không cần tạo nhiều class. Ngoài ra sử dụng Strategy Pattern để tạo các hành vi khác nhau cho các object quái mà không cần tạo nhiều class.

### Kết Quả

- Sau khi sử dụng Builder và Strategy Pattern, việc tạo các object quái đã trở nên dễ dàng hơn, không cần tạo nhiều class. Có thể chỉ cần config các thuộc tính và hành vi cho object quái mà không cần tạo nhiều class.

## 7. Kết Luận

**Kết quả đạt được:** [Mô tả kết quả đạt được sau khi giải quyết các vấn đề]

**Hướng phát triển tiếp theo:** [Mô tả hướng phát triển tiếp theo của dự án]