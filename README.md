# Quản lý phòng tập gym 
BTL: Môn HQT  CSDL --Thông Tin Cá nhân--
•	Họ và tên: Lành Đức Mạnh
•	Lớp: K57KMT.01
•	MSSV: K215480106108
I.Mô tả bài toán quản lí: xây dựng một hệ thống quản lý phòng tập gym hiệu quả thông qua việc thiết kế và quản lý cơ sở dữ liệu bằng SQL. Hệ thống này cần có khả năng lưu trữ, cập nhật, truy vấn và quản lý các thông tin liên quan đến hội viên, huấn luyện viên, lớp học, thiết bị và các hoạt động đăng ký lớp học.
## Những chức năng Bài toán xây dựng CSDL để quản lý phòng tập gym.
1 Quản lý thông tin thành viên (Members)
   - Thêm, sửa, xóa thông tin thành viên.
   - Tra cứu thông tin thành viên như họ tên, ngày sinh, giới tính, số điện thoại, email, ngày bắt đầu và ngày kết thúc thành viên.
2 Quản lý thông tin huấn luyện viên (Trainers)
   - Thêm, sửa, xóa thông tin huấn luyện viên.
   - Tra cứu thông tin huấn luyện viên như họ tên, số điện thoại, email, chuyên môn và ngày tuyển dụng.
3 Quản lý lớp học (Classes)
   - Thêm, sửa, xóa thông tin lớp học.
   - Tra cứu thông tin lớp học như tên lớp, lịch học, huấn luyện viên phụ trách và số lượng học viên tối đa.
4 Quản lý đăng ký lớp học (Class Registrations)
   - Đăng ký thành viên vào các lớp học.
   - Hủy đăng ký lớp học.
   - Tra cứu thông tin đăng ký lớp học của các thành viên.
5 Quản lý thiết bị (Equipment)
   - Thêm, sửa, xóa thông tin thiết bị.
   - Tra cứu thông tin thiết bị như tên thiết bị, ngày mua và tình trạng hiện tại.
6 Quản lý thanh toán (Payments)
   - Thêm, sửa, xóa thông tin thanh toán.
   - Tra cứu thông tin thanh toán của các thành viên, bao gồm ngày thanh toán, số tiền và phương thức thanh toán.
##Nhập, Xuất và Báo cáo trong Bài toán Quản lý Phòng tập Gym bằng SQL
Nhập Dữ Liệu
1.Khách hàng (Customers)
   - Nhập thông tin khách hàng mới: Họ tên, ngày sinh, email, số điện thoại, ngày bắt đầu và ngày kết thúc thành viên.
   - Cập nhật thông tin khách hàng hiện tại.
   - Gia hạn thành viên cho khách hàng.
2. Huấn luyện viên (Trainers)
   - Nhập thông tin huấn luyện viên mới: Họ tên, email, số điện thoại, ngày tuyển dụng.
   - Cập nhật thông tin huấn luyện viên hiện tại.
3. Lớp học (Classes)
   - Nhập thông tin lớp học mới: Tên lớp học, mô tả, lịch học.
   - Cập nhật thông tin lớp học hiện tại.
4. Lịch tập (Schedule)
   - Nhập lịch tập mới: Chọn lớp học, huấn luyện viên, ngày và giờ diễn ra lớp, địa điểm.
   - Cập nhật lịch tập hiện tại.
5. Đăng ký (Registrations)
   - Nhập thông tin đăng ký mới: Chọn khách hàng, lịch tập, ngày đăng ký.
   - Cập nhật thông tin đăng ký hiện tại.
 Xuất Dữ Liệu
1. Khách hàng (Customers)
   - Xuất danh sách khách hàng kèm thông tin chi tiết.
   - Xuất danh sách khách hàng sắp hết hạn thành viên.
2. Huấn luyện viên (Trainers)
   - Xuất danh sách huấn luyện viên kèm thông tin chi tiết.
   - Xuất danh sách huấn luyện viên theo ngày tuyển dụng.
3. Lớp học (Classes)
   - Xuất danh sách lớp học kèm mô tả và lịch học.
   - Xuất danh sách lớp học theo huấn luyện viên.
4. Lịch tập (Schedule)
   - Xuất lịch tập chi tiết bao gồm lớp học, huấn luyện viên, ngày giờ, địa điểm.
   - Xuất lịch tập theo lớp học hoặc theo huấn luyện viên.
5. Đăng ký (Registrations)
   - Xuất danh sách đăng ký kèm thông tin khách hàng và lịch tập.
   - Xuất danh sách đăng ký theo lớp học hoặc theo khách hàng.
 Báo Cáo
1. Báo cáo khách hàng
   - Báo cáo số lượng khách hàng mới trong khoảng thời gian nhất định.
   - Báo cáo số lượng khách hàng sắp hết hạn thành viên.
2. Báo cáo huấn luyện viên
   - Báo cáo số lượng huấn luyện viên mới tuyển dụng trong khoảng thời gian nhất định.
   - Báo cáo hiệu suất làm việc của huấn luyện viên dựa trên số lượng lớp học đã hướng dẫn.
3. Báo cáo lớp học
   - Báo cáo số lượng lớp học được tổ chức trong khoảng thời gian nhất định.
   - Báo cáo số lượng học viên tham gia từng lớp học.
4. Báo cáo lịch tập
   - Báo cáo tổng số lớp học theo từng khoảng thời gian.
   - Báo cáo lịch tập theo từng huấn luyện viên hoặc từng lớp học.
5. Báo cáo đăng ký
   - Báo cáo số lượng đăng ký mới trong khoảng thời gian nhất định.
   - Báo cáo tình hình tham gia các lớp học của từng khách hàng.
1. Sản phẩm sẽ quản lý những thông tin như sau 🔑MaThanhVien,HoTen,NgaySinh,GioiTinh,SoDienThoai,Egmail,NgayBatDauThanhVien,NgayKetThucThanhVien.
2. 🔑MaHuyenLuyenVien,HoTen,SoDienThoai,Egmail,ChuyenMon,NgayTuyenDung.
3. 🔑MaLopHoc,TenLopHoc,MaHuanLuyenVien,LichHoc,SoLuongHocVienToiDa.
4. 🔑MaDangKi,MaThanhVien,MaLopHoc,NgayDangKi.
5. 🔑MaThietBi,TenThietBi,NgayMua,TinhTrang.
6. 🔑MaThanhToan,MaThanhVien,NgayThanhToan,SoTien,PhuongThucThanhToan.
Tạo các bảng trong SQL:

1. Bảng thành viên.

![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/f3aa020c-4afe-4a9e-b4f2-c2c4038404cb)

 
2. Bảng huấn luyện viên.

   ![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/7f7333c3-e945-44af-9d16-01e4ccb7a026)

 
3. Bảng lớp học.

 ![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/4b6a061d-e7ae-49c4-9813-61a37905331d)

4. Bảng đăng ký lớp học.

 ![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/456aa87d-55a0-4dbf-af51-6d5008b26709)

5. Bảng thiết bị.

 ![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/1aa3c0a0-d1f0-440d-bf6b-4ee06ac3f171)

6. Bảng thanh toán.

 ![image](https://github.com/lanhducmanh/QuanLyPhongGym/assets/170821456/f21d470a-020f-4ddf-9d39-c9598e4719fa)


Tạo sơ đồ thực thể liên kết giữa các bảng :

Thêm dữ liệu vào các bảng : 
1. Thêm thành viên mẫu
INSERT INTO ThanhVien (Ho, Ten, NgaySinh, GioiTinh, SoDienThoai, Email, NgayBatDauThanhVien, NgayKetThucThanhVien)
VALUES 
('Nguyen', 'Van A', '1990-01-01', 'M', '0123456789', 'van.a@example.com', '2024-01-01', '2024-12-31'),
('Tran', 'Thi B', '1985-05-15', 'F', '0987654321', 'thi.b@example.com', '2024-01-01', '2024-12-31');

2. Thêm huấn luyện viên mẫu
INSERT INTO HuanLuyenVien (Ho, Ten, SoDienThoai, Email, ChuyenMon, NgayTuyenDung)
VALUES 
('Nguyen', 'Thi C', '1112223333', 'thi.c@example.com', 'Yoga', '2020-01-01'),
('Le', 'Van D', '4445556666', 'van.d@example.com', 'Weightlifting', '2021-05-10');

3. Thêm lớp học mẫu
INSERT INTO LopHoc (TenLopHoc, MaHuanLuyenVien, LichHoc, SoLuongHocVienToiDa)
VALUES 
('Yoga Buổi Sáng', 1, 'T2, T4, T6 7:00 AM - 8:00 AM', 20),
('Tập Tạ Buổi Tối', 2, 'T3, T5 6:00 PM - 7:30 PM', 15);

4. Thêm thiết bị mẫu
INSERT INTO ThietBi (TenThietBi, NgayMua, TinhTrang)
VALUES 
('Máy chạy bộ', '2023-01-15', 'Tốt'),
('Tạ tay', '2022-08-20', 'Xuất sắc');

5. Thêm thanh toán mẫu
INSERT INTO ThanhToan (MaThanhVien, NgayThanhToan, SoTien, PhuongThucThanhToan)
VALUES 
(1, '2024-01-01', 100.00, 'Thẻ tín dụng'),
(2, '2024-01-01', 100.00, 'Thẻ tín dụng');

6. Đăng ký lớp học mẫu
INSERT INTO DangKyLopHoc (MaThanhVien, MaLopHoc, NgayDangKy)
VALUES 
(1, 1, '2024-01-01'),
(2, 2, '2024-01-02');
GO
## XÂY DỰNG CÁC THỦ TỤC THEO CÁC CHỨC NĂNG MONG MUỐN.
1. Quản lý thông tin thành viên (Members)
- Thêm, Sửa, xóa, tra cứu thành viên:
2. Quản lý thông tin huấn luyện viên (Trainers)
- Thêm, Sửa, xóa, tra cứu huấn luyện viên:
3. Quản lý lớp học (Classes)
- Thêm, Sửa, xóa, tra cứu  lớp học:
4. Quản lý đăng ký lớp học (Class Registrations)
-đăng ký, hủy đăng kí, tra cứu thông tin đăng kí, lớp học:
5. Quản lý thiết bị (Equipment)
Thêm,sửa,xóa thiết bị:
-------------------------
1.1	Quản lý thông tin thành viên (Members)
-Thêm thành viên.
 
--Tạo thủ tục thêm thành viên
CREATE PROCEDURE ThemThanhVien
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @NgaySinh DATE,
    @GioiTinh CHAR(1),
    @SoDienThoai NVARCHAR(15),
    @Email NVARCHAR(100),
    @NgayBatDauThanhVien DATE,
    @NgayKetThucThanhVien DATE
AS
BEGIN
    INSERT INTO ThanhVien (Ho, Ten, NgaySinh, GioiTinh, SoDienThoai, Email, NgayBatDauThanhVien, NgayKetThucThanhVien)
    VALUES (@Ho, @Ten, @NgaySinh, @GioiTinh, @SoDienThoai, @Email, @NgayBatDauThanhVien, @NgayKetThucThanhVien);
END;
GO
-sử dụng thủ tục
 
-Thành viên đã được thêm vào.
 
-Sửa thông tin thành viên:
CREATE PROCEDURE SuaThanhVien
    @MaThanhVien INT,
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @NgaySinh DATE,
    @GioiTinh CHAR(1),
    @SoDienThoai NVARCHAR(15),
    @Email NVARCHAR(100),
    @NgayBatDauHoiVien DATE,
    @NgayKetThucHoiVien DATE
AS
BEGIN
    UPDATE ThanhVien
    SET Ho = @Ho,
        Ten = @Ten,
        NgaySinh = @NgaySinh,
        GioiTinh = @GioiTinh,
        SoDienThoai = @SoDienThoai,
        Email = @Email,
        NgayBatDauHoiVien = @NgayBatDauHoiVien,
        NgayKetThucHoiVien = @NgayKetThucHoiVien
    WHERE MaThanhVien = @MaThanhVien;
END;


Xóa thành viên:
```sql
CREATE PROCEDURE XoaThanhVien
    @MaThanhVien INT
AS
BEGIN
    DELETE FROM ThanhVien
    WHERE MaThanhVien = @MaThanhVien;
END;
GO
```

**Tra cứu thông tin thành viên:**
```sql
CREATE PROCEDURE TraCuuThanhVien
    @MaThanhVien INT
AS
BEGIN
    SELECT Ho, Ten, NgaySinh, GioiTinh, SoDienThoai, Email, NgayBatDauHoiVien, NgayKetThucHoiVien
    FROM ThanhVien
    WHERE MaThanhVien = @MaThanhVien;
END;
GO
```

1.2 Quản lý thông tin huấn luyện viên (Trainers)

**Thêm huấn luyện viên:**
```sql
CREATE PROCEDURE ThemHuanLuyenVien
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @SoDienThoai NVARCHAR(15),
    @Email NVARCHAR(100),
    @NgayTuyenDung DATE,
    @ChuyenMon NVARCHAR(100)
AS
BEGIN
    INSERT INTO HuanLuyenVien (Ho, Ten, SoDienThoai, Email, NgayTuyenDung, ChuyenMon)
    VALUES (@Ho, @Ten, @SoDienThoai, @Email, @NgayTuyenDung, @ChuyenMon);
END;
GO
```

**Sửa thông tin huấn luyện viên:**
```sql
CREATE PROCEDURE SuaHuanLuyenVien
    @MaHuanLuyenVien INT,
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @SoDienThoai NVARCHAR(15),
    @Email NVARCHAR(100),
    @NgayTuyenDung DATE,
    @ChuyenMon NVARCHAR(100)
AS
BEGIN
    UPDATE HuanLuyenVien
    SET Ho = @Ho,
        Ten = @Ten,
        SoDienThoai = @SoDienThoai,
        Email = @Email,
        NgayTuyenDung = @NgayTuyenDung,
        ChuyenMon = @ChuyenMon
    WHERE MaHuanLuyenVien = @MaHuanLuyenVien;
END;
GO
```

**Xóa huấn luyện viên:**
```sql
CREATE PROCEDURE XoaHuanLuyenVien
    @MaHuanLuyenVien INT
AS
BEGIN
    DELETE FROM HuanLuyenVien
    WHERE MaHuanLuyenVien = @MaHuanLuyenVien;
END;
GO
```

**Tra cứu thông tin huấn luyện viên:**
```sql
CREATE PROCEDURE TraCuuHuanLuyenVien
    @MaHuanLuyenVien INT
AS
BEGIN
    SELECT Ho, Ten, SoDienThoai, Email, ChuyenMon, NgayTuyenDung
    FROM HuanLuyenVien
    WHERE MaHuanLuyenVien = @MaHuanLuyenVien;
END;
GO
```

### 1.3 Quản lý lớp học (Classes)

**Thêm lớp học:**
```sql
CREATE PROCEDURE ThemLopHoc
    @TenLop NVARCHAR(50),
    @MaHuanLuyenVien INT,
    @LichHoc NVARCHAR(100),
    @SoLuongHocVienToiDa INT
AS
BEGIN
    INSERT INTO LopHoc (TenLop, MaHuanLuyenVien, LichHoc, SoLuongHocVienToiDa)
    VALUES (@TenLop, @MaHuanLuyenVien, @LichHoc, @SoLuongHocVienToiDa);
END;
GO
```

**Sửa thông tin lớp học:**
```sql
CREATE PROCEDURE SuaLopHoc
    @MaLopHoc INT,
    @TenLop NVARCHAR(50),
    @MaHuanLuyenVien INT,
    @LichHoc NVARCHAR(100),
    @SoLuongHocVienToiDa INT
AS
BEGIN
    UPDATE LopHoc
    SET TenLop = @TenLop,
        MaHuanLuyenVien = @MaHuanLuyenVien,
        LichHoc = @LichHoc,
        SoLuongHocVienToiDa = @SoLuongHocVienToiDa
    WHERE MaLopHoc = @MaLopHoc;
END;
GO
```

**Xóa lớp học:**
```sql
CREATE PROCEDURE XoaLopHoc
    @MaLopHoc INT
AS
BEGIN
    DELETE FROM LopHoc
    WHERE MaLopHoc = @MaLopHoc;
END;
GO
```

**Tra cứu thông tin lớp học:**
```sql
CREATE PROCEDURE TraCuuLopHoc
    @MaLopHoc INT
AS
BEGIN
    SELECT TenLop, LichHoc, MaHuanLuyenVien, SoLuongHocVienToiDa
    FROM LopHoc
    WHERE MaLopHoc = @MaLopHoc;
END;
GO
```

### 1.4 Quản lý đăng ký lớp học (Class Registrations)

**Đăng ký lớp học:**
```sql
CREATE PROCEDURE DangKyLopHoc
    @MaThanhVien INT,
    @MaLopHoc INT,
    @NgayDangKy DATE
AS
BEGIN
    INSERT INTO DangKyLopHoc (MaThanhVien, MaLopHoc, NgayDangKy)
    VALUES (@MaThanhVien, @MaLopHoc, @NgayDangKy);
END;
GO
```

**Hủy đăng ký lớp học:**
```sql
CREATE PROCEDURE HuyDangKyLopHoc
    @MaDangKy INT
AS
BEGIN
    DELETE FROM DangKyLopHoc
    WHERE MaDangKy = @MaDangKy;
END;
GO
```

**Tra cứu thông tin đăng ký lớp học:**
```sql
CREATE PROCEDURE TraCuuDangKyLopHoc
    @MaThanhVien INT
AS
BEGIN
    SELECT MaDangKy, MaLopHoc, NgayDangKy
    FROM DangKyLopHoc
    WHERE MaThanhVien = @MaThanhVien;
END;
GO
```

### 1.5 Quản lý thiết bị (Equipment)

**Thêm thiết bị:**
```sql
CREATE PROCEDURE ThemThietBi
    @TenThietBi NVARCHAR(50),
    @NgayMua DATE,
    @TinhTrang NVARCHAR(50)
AS
BEGIN
    INSERT INTO ThietBi (TenThietBi, NgayMua, TinhTrang)
    VALUES (@TenThietBi, @NgayMua, @TinhTrang);
END;
GO
```

**Sửa thông tin thiết bị:**
```sql
CREATE PROCEDURE SuaThietBi
    @MaThietBi INT,
    @TenThietBi NVARCHAR(50),
    @NgayMua DATE,
    @TinhTrang NVARCHAR(50)
AS
BEGIN
    UPDATE ThietBi
    SET TenThietBi = @TenThietBi,
        NgayMua = @NgayMua,
        TinhTrang = @TinhTrang
    WHERE MaThietBi = @MaThietBi;
END;
GO
```

**Xóa thiết bị:**
```sql
CREATE PROCEDURE XoaThietBi
    @MaThietBi INT
AS
BEGIN
    DELETE FROM ThietBi
    WHERE MaThietBi = @MaThietBi;
END;
GO
``




