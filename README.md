TRƯỜNG ĐẠI HỌC KỸ THUẬT CÔNG NGHIỆP
KHOA ĐIỆN TỬ
BỘ MÔN: CÔNG NGHỆ THÔNG TIN
 
BÀI TẬP LỚN MÔN HỌC HỆ QUẢN TRỊ CƠ SỞ DỮ LIỆU
Giảng viên hướng dẫn	:	ĐỖ DUY CỐP
Họ tên sinh viên	:	LÀNH ĐỨC MẠNH
Ngành học	:	Kỹ thuật Máy tínhvv
MSSV	:	K215480106108
Lớp	:	K57KMT.01


 


TRƯỜNG ĐẠI HỌC KTCN                          CỘNG HOÀ XÃ HỘI CHỦ NGHĨA VIỆT NAM                    
         KHOA ĐIỆN TỬ         	                                         Độc lập - Tự do - Hạnh phúc 
BỘ MÔN CÔNG NGHỆ THÔNG TIN
PHIẾU GIAO ĐỀ TÀI MÔN CSDL
Sinh viên: Lành Đức Mạnh.
MSSV: K215480106108 
Lớp: K57KMT.                               Ngành: Kỹ thuật máy tính
Giáo viên hướng dẫn: Đỗ Duy Cốp 
Tên đề tài : Quản lý phòng tập gym 
Yêu cầu : -Tạo các bảng cơ sở dữ liệu: Thiết kế và tạo các bảng để lưu trữ thông tin cần thiết cho quản lý phòng tập.
-Quản lý thành viên.
-Quản lý huấn luyện viên.
-Quản lý lớp học.
-Quản lý đăng ký lớp học.
-Quản lý thiết bị.
-Quản lý thanh toán.

	    GIÁO VIÊN HƯỚNG DẪN
(Ký và ghi rõ họ tên)






1. Thông Tin về sinh viên. Họ tên :Lành Đức Mạnh Mã SV : K215480106108 Lớp K57KMT Bài tập lớn môn học : Hệ quản trị cơ sở dữ liệu.
2. Thông tin về bài toán Project csdl cho bài toán:Quản lýphòng tập gym. Mô tả về bài toán: xây dựng một hệ thống quản lý phòng tập gym hiệu quả thông qua việc thiết kế và quản lý cơ sở dữ liệu bằng SQL. Hệ thống này cần có khả năng lưu trữ, cập nhật, truy vấn và quản lý các thông tin liên quan đến hội viên, huấn luyện viên, lớp học, thiết bị và các hoạt động đăng ký lớp học.
I.Chức Năng:

1. Quản lý thông tin thành viên (Members)
   - Thêm, sửa, xóa thông tin thành viên.
   - Tra cứu thông tin thành viên như họ tên, ngày sinh, giới tính, số điện thoại, email, ngày bắt đầu và ngày kết thúc thành viên.
2. Quản lý thông tin huấn luyện viên (Trainers)
   - Thêm, sửa, xóa thông tin huấn luyện viên.
   - Tra cứu thông tin huấn luyện viên như họ tên, số điện thoại, email, chuyên môn và ngày tuyển dụng.
3. Quản lý lớp học (Classes)
   - Thêm, sửa, xóa thông tin lớp học.
   - Tra cứu thông tin lớp học như tên lớp, lịch học, huấn luyện viên phụ trách và số lượng học viên tối đa.
4. Quản lý đăng ký lớp học (Class Registrations)
   - Đăng ký thành viên vào các lớp học.
   - Hủy đăng ký lớp học.
   - Tra cứu thông tin đăng ký lớp học của các thành viên.
5. Quản lý thiết bị (Equipment)
   - Thêm, sửa, xóa thông tin thiết bị.
   - Tra cứu thông tin thiết bị như tên thiết bị, ngày mua và tình trạng hiện tại.
6. Quản lý thanh toán (Payments)
   - Thêm, sửa, xóa thông tin thanh toán.
   - Tra cứu thông tin thanh toán của các thành viên, bao gồm ngày thanh toán, số tiền và phương thức thanh toán.
II. Nhập, Xuất và Báo cáo các thông tin về Quản lý Phòng tập Gym.
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
 Các Truy Vấn SQL Ví Dụ
Dưới đây là một số truy vấn SQL để thực hiện các chức năng nhập, xuất và báo cáo:
1. Xuất danh sách khách hàng sắp hết hạn thành viên:
SELECT * FROM Customers
WHERE MembershipEndDate <= DATEADD(month, 1, GETDATE());
2. Báo cáo số lượng khách hàng mới trong tháng này:
SELECT COUNT(*) AS NewCustomersThisMonth
FROM Customers
WHERE MONTH(MembershipStartDate) = MONTH(GETDATE())
  AND YEAR(MembershipStartDate) = YEAR(GETDATE());
3. Báo cáo số lượng lớp học trong tuần này:
SELECT COUNT(*) AS ClassesThisWeek
FROM Schedule
WHERE DATEPART(week, ClassDate) = DATEPART(week, GETDATE())
  AND YEAR(ClassDate) = YEAR(GETDATE());
4. Xuất danh sách đăng ký theo khách hàng:
SELECT r.RegistrationID, c.FirstName, c.LastName, s.ClassDate, cl.ClassName
FROM Registrations r
JOIN Customers c ON r.CustomerID = c.CustomerID
JOIN Schedule s ON r.ScheduleID = s.ScheduleID
JOIN Classes cl ON s.ClassID = cl.ClassID
ORDER BY c.LastName, c.FirstName;
III. Bảng dữ liệu cần thiết cho quản lý phòng tập gym
Bảng: Customers (Khách hàng)
- CustomerID (PK): INT, tự động tăng, khóa chính.
- FirstName: NVARCHAR(50), không được để trống.
- LastName: NVARCHAR(50), không được để trống.
- DateOfBirth: DATE, không được để trống.
- Email: NVARCHAR(100), không được để trống, duy nhất.
- PhoneNumber: NVARCHAR(15), có thể để trống.
- MembershipStartDate: DATE, không được để trống.
- MembershipEndDate: DATE, có thể để trống.

Bảng: Trainers (Huấn luyện viên)
- TrainerID(PK): INT, tự động tăng, khóa chính.
- FirstName: NVARCHAR(50), không được để trống.
- LastName: NVARCHAR(50), không được để trống.
- Email: NVARCHAR(100), không được để trống, duy nhất.
- PhoneNumber: NVARCHAR(15), có thể để trống.
- HireDate: DATE, không được để trống.

Bảng: Classes (Lớp học)
- ClassID(PK): INT, tự động tăng, khóa chính.
- ClassName: NVARCHAR(100), không được để trống.
- Description: NVARCHAR(255), có thể để trống.
- Schedule: NVARCHAR(100), không được để trống.

    Bảng: Schedule (Lịch tập)
-ScheduleID (PK): INT, tự động tăng, khóa chính.
- ClassID (FK): INT, không được để trống, khóa ngoại tham chiếu đến Classes(ClassID).
- TrainerID (FK): INT, không được để trống, khóa ngoại tham chiếu đến Trainers(TrainerID).
- ClassDate: DATETIME, không được để trống.
- Location: NVARCHAR(100), không được để trống.

Bảng: Registrations (Đăng ký)
- RegistrationID (PK): INT, tự động tăng, khóa chính.
- CustomerID (FK): INT, không được để trống, khóa ngoại tham chiếu đến Customers(CustomerID).
- ScheduleID (FK): INT, không được để trống, khóa ngoại tham chiếu đến Schedule(ScheduleID).
- RegistrationDate: DATETIME, không được để trống.

Ràng buộc kiểm tra (CK)
Trong đoạn mã trên, không có ràng buộc kiểm tra (CK) cụ thể được định nghĩa. Tuy nhiên, có thể thêm các ràng buộc kiểm tra nếu cần thiết, chẳng hạn như:
- DateOfBirth phải nhỏ hơn ngày hiện tại.
- MembershipEndDate phải lớn hơn hoặc bằng MembershipStartDate.

Ví dụ thêm ràng buộc kiểm tra vào bảng Customers:
ALTER TABLE Customers
ADD CONSTRAINT CK_Customers_DateOfBirth CHECK (DateOfBirth < GETDATE());

ALTER TABLE Customers
ADD CONSTRAINT CK_Customers_MembershipDates CHECK (MembershipEndDate >= MembershipStartDate);

 Mô hình quan hệ
- Customers liên kết với Registrations thông qua CustomerID.
- Trainers liên kết với Schedule thông qua TrainerID.
- Classes liên kết với Schedule thông qua ClassID.
- Schedule liên kết với Registrations thông qua ScheduleID.

 Sơ đồ ER (Entity-Relationship Diagram)
1. Customers (1) - (n) Registrations
2. Trainers (1) - (n) Schedule
3. Classes (1) - (n) Schedule
4. Schedule (1) - (n) Registrations
IV. Với mỗi chức năng, hoạc nhóm chức năng : tạo SP_ để hỗ trợ.
Nhập Dữ Liệu
1. Nhập thông tin khách hàng mới
CREATE PROCEDURE SP_ThemKhachHang
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @NgaySinh DATE,
    @Email NVARCHAR(100),
    @SoDienThoai NVARCHAR(15) = NULL,
    @NgayBatDauThanhVien DATE,
    @NgayKetThucThanhVien DATE = NULL
AS
BEGIN
    INSERT INTO Customers (FirstName, LastName, DateOfBirth, Email, PhoneNumber, MembershipStartDate, MembershipEndDate)
    VALUES (@Ho, @Ten, @NgaySinh, @Email, @SoDienThoai, @NgayBatDauThanhVien, @NgayKetThucThanhVien);
END
GO
2. Nhập thông tin huấn luyện viên mới
CREATE PROCEDURE SP_ThemHLV
    @Ho NVARCHAR(50),
    @Ten NVARCHAR(50),
    @Email NVARCHAR(100),
    @SoDienThoai NVARCHAR(15) = NULL,
    @NgayTuyenDung DATE
AS
BEGIN
    INSERT INTO Trainers (FirstName, LastName, Email, PhoneNumber, HireDate)
    VALUES (@Ho, @Ten, @Email, @SoDienThoai, @NgayTuyenDung);
END
GO

3. Nhập thông tin lớp học mới
CREATE PROCEDURE SP_ThemLopHoc
    @TenLopHoc NVARCHAR(100),
    @MoTa NVARCHAR(255) = NULL,
    @LichHoc NVARCHAR(100)
AS
BEGIN
    INSERT INTO Classes (ClassName, Description, Schedule)
    VALUES (@TenLopHoc, @MoTa, @LichHoc);
END
GO

4. Nhập lịch tập mới
CREATE PROCEDURE SP_ThemLichTap
    @LopHocID INT,
    @HLVID INT,
    @NgayGioLop DATETIME,
    @DiaDiem NVARCHAR(100)
AS
BEGIN
    INSERT INTO Schedule (ClassID, TrainerID, ClassDate, Location)
    VALUES (@LopHocID, @HLVID, @NgayGioLop, @DiaDiem);
END
GO

5. Nhập thông tin đăng ký mới
CREATE PROCEDURE SP_ThemDangKy
    @KhachHangID INT,
    @LichTapID INT,
    @NgayDangKy DATETIME
AS
BEGIN
    INSERT INTO Registrations (CustomerID, ScheduleID, RegistrationDate)
    VALUES (@KhachHangID, @LichTapID, @NgayDangKy);
END
GO

Xuất Dữ Liệu
1. Xuất danh sách khách hàng kèm thông tin chi tiết
CREATE PROCEDURE SP_LayDanhSachKhachHang
AS
BEGIN
    SELECT * FROM Customers;
END
GO

2. Xuất danh sách khách hàng sắp hết hạn thành viên
CREATE PROCEDURE SP_LayDanhSachKhachHangSapHetHan
AS
BEGIN
    SELECT * FROM Customers
    WHERE MembershipEndDate <= DATEADD(month, 1, GETDATE());
END
GO
3. Xuất danh sách huấn luyện viên kèm thông tin chi tiết
CREATE PROCEDURE SP_LayDanhSachHLV
AS
BEGIN
    SELECT * FROM Trainers;
END
GO

4. **Xuất danh sách lớp học kèm mô tả và lịch học**
CREATE PROCEDURE SP_LayDanhSachLopHoc
AS
BEGIN
    SELECT * FROM Classes;
END
GO
5. Xuất lịch tập chi tiết
CREATE PROCEDURE SP_LayDanhSachLichTap
AS
BEGIN
    SELECT s.ScheduleID, c.ClassName, t.FirstName + ' ' + t.LastName AS TrainerName, s.ClassDate, s.Location
    FROM Schedule s
    JOIN Classes c ON s.ClassID = c.ClassID
    JOIN Trainers t ON s.TrainerID = t.TrainerID;
END
GO
6. Xuất danh sách đăng ký theo khách hàng
CREATE PROCEDURE SP_LayDangKyTheoKhachHang
AS
BEGIN
    SELECT r.RegistrationID, c.FirstName, c.LastName, s.ClassDate, cl.ClassName
    FROM Registrations r
    JOIN Customers c ON r.CustomerID = c.CustomerID
    JOIN Schedule s ON r.ScheduleID = s.ScheduleID
    JOIN Classes cl ON s.ClassID = cl.ClassID
    ORDER BY c.LastName, c.FirstName;
END
GO
 Báo Cáo
1. Báo cáo số lượng khách hàng mới trong tháng này
CREATE PROCEDURE SP_BaoCaoKhachHangMoiThangNay
AS
BEGIN
    SELECT COUNT(*) AS KhachHangMoiThangNay
    FROM Customers
    WHERE MONTH(MembershipStartDate) = MONTH(GETDATE())
      AND YEAR(MembershipStartDate) = YEAR(GETDATE());
END
GO
2. Báo cáo số lượng lớp học trong tuần này
CREATE PROCEDURE SP_BaoCaoLopHocTuanNay
AS
BEGIN
    SELECT COUNT(*) AS LopHocTuanNay
    FROM Schedule
    WHERE DATEPART(week, ClassDate) = DATEPART(week, GETDATE())
      AND YEAR(ClassDate) = YEAR(GETDATE());
END
GO
3. Báo cáo số lượng khách hàng sắp hết hạn thành viên
CREATE PROCEDURE SP_BaoCaoThanhVienSapHetHan
AS
BEGIN
    SELECT COUNT(*) AS ThanhVienSapHetHan
    FROM Customers
    WHERE MembershipEndDate <= DATEADD(month, 1, GETDATE());
END
GO
4. Báo cáo số lượng đăng ký mới trong tháng này
CREATE PROCEDURE SP_BaoCaoDangKyMoiThangNay
AS
BEGIN
    SELECT COUNT(*) AS DangKyMoiThangNay
    FROM Registrations
    WHERE MONTH(RegistrationDate) = MONTH(GETDATE())
      AND YEAR(RegistrationDate) = YEAR(GETDATE());
END
GO
