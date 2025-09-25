<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#

## [v.3.25.0925.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung chức năng ngưng sử dụng mã máy thực hiện cls (BV Thanh Bình)
- ✨: Khi load danh sách máy thực hiện CLS thêm điều kiện xoa = 0.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/448

## [v.3.25.0923.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509230-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thêm hình ảnh chuyển thành base64 truyền vào ký số EMR - build lại
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

![](https://i.vgy.me/nWUm2U.png)

## [v.3.25.0922.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509220-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bổ sung xử lý chuyển hình ảnh sang Base64 add vào Json Ký số EMR tại ClsHinhAnh
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

- Thêm thông tin PCReqDltVoucherNo.
- Thêm thông tin UOMName.
- Đổi định dạng NgayChiDinh,NgayThucHien, NgayKetQua sang yyyy-MM-dd HH24:mm:ss
- Nếu có hình ảnh kết quả sẽ chuyển thành Base64 với IMAGE thứ tự tăng dần.

![](https://i.vgy.me/PkqD0h.png)

![](https://i.vgy.me/GcBv39.png)

## [v.3.25.0919.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509191-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509191-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509191-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- ✨: Fix lỗi - khi in ký số EMR thì lable ##{S1}##,##{S2}## đổi sang màu trắng nhưng khi in thường thì vẫn là màu đen
![](https://i.vgy.me/DFRtqy.gif)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0919.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509190-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thử nghiệm Bổ sung thông tin XML để ký số EMR
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

![](https://i.vgy.me/lPnpqd.png)

## [v.3.25.0917.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509171-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509171-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509171-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- ✨: Thêm thông báo khi không tìm thấy loại phiếu
![](https://i.vgy.me/3IaLuP.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0917.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509170-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi kết quả XQuang
	- Cập nhật
	![](https://i.vgy.me/THx1lg.png)
	![](https://i.vgy.me/YAdeCC.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/519

## [v.3.25.0916.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509161-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509161-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509161-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diangose: Tài khoản bác sĩ không có đăng ký Chữ ký số trả kết quả báo lỗi #519
	- Cập nhật: kiểm tra và cập nhật script

	![](https://i.vgy.me/SNCzne.png)
	![](https://i.vgy.me/5uwVVB.png)
	![](https://i.vgy.me/RukfzX.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/519
<<<<<<< HEAD

## [v.3.25.0916.0]()
- 🐛: Lỗi - Diangose: Tài khoản bác sĩ không có đăng ký Chữ ký số trả kết quả báo lỗi #519
	- Cập nhật:
	![](https://i.vgy.me/5uwVVB.png)
	![](https://i.vgy.me/RukfzX.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/519
=======

## [v.3.25.0915.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509152-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509152-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509152-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- 🐛: Fix lỗi khi in ký số EMR, phần lable đặt chữ ký chưa đổ sang màu trắng
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0915.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509151-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509151-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509151-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- 🐛: Fix lỗi ký số EMR - phát sinh lỗi khi update lại xmlreport
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0915.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509150-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi: HIS hiển thị thiếu thông tin CLS Chẩn đoán hình ảnh
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/16
- 📕: Xử lý nếu nhận kết quả từ EMR `api = 1` và `filePath != ''` thì view kết quả từ EMR tại DH.ReportCLS.KetQua.HA.ClsHinhAnh.Preview()

![](https://i.vgy.me/kLjcNe.png)

![](https://i.vgy.me/vB93XT.png)

![](https://i.vgy.me/bae1G6.png)

## [v.3.25.0914.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509140-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
	- Tích hợp ký số:
	- XQ:
	![](https://i.vgy.me/SF5beo.png)

	- Siêu âm:
	![](https://i.vgy.me/ZKsWAc.png)

	- Điện tim:
	![](https://i.vgy.me/6TD5GM.png)

	- Nội soi
	![](https://i.vgy.me/VBKJQn.png)

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0911.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509110-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Yêu cầu - Diagnose: Bổ sung chức năng xuất file excel Danh mục bệnh lý. #417
	- Cập nhật: build lại
	
	![](https://i.vgy.me/zH4eF9.png)
	![](https://i.vgy.me/OOnGpV.png)
	![](https://i.vgy.me/Xo22hm.png)
	
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/417

## [v.3.25.0910.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509101-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509101-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509101-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Yêu cầu - Diagnose: Bổ sung chức năng xuất file excel Danh mục bệnh lý. #417
	- Cập nhật:
	
	![](https://i.vgy.me/zH4eF9.png)
	![](https://i.vgy.me/OOnGpV.png)
	![](https://i.vgy.me/Xo22hm.png)
	
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/417
<<<<<<< HEAD

## [v.3.25.0910.0]()
- 🐛: Yêu cầu - Diagnose: Bổ sung chức năng xuất file excel Danh mục bệnh lý. #417
	- Cập nhật:
	
	![](https://i.vgy.me/zH4eF9.png)
	![](https://i.vgy.me/OOnGpV.png)
	![](https://i.vgy.me/Xo22hm.png)
	
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/417
=======

## [v.3.25.0909.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509090-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module liên quan hoàn thiện Chữ ký số theo cách mới
- ✨: Bổ sung ký số Phiếu Kết quả XQuang 
![](https://i.vgy.me/DWOnCK.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/436

## [v.3.25.0908.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32509080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Các module liên quan hoàn thiện Chữ ký số theo cách mới
![](https://i.vgy.me/uPoIzU.png)
![](https://i.vgy.me/jvWZa2.png)
![](https://i.vgy.me/8G6Uif.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/436

## [v.3.25.0820.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508200-NasDHSolutions.json)</sup></sup></sub>
	- Fix lỗi:
	  
	  + Không check xóa thư mục
	  ![](https://i.vgy.me/lwsS9g.png)
	  
	  + Fix Có cấu hình xóa thư mục chứa hình --> không xóa được hình
	  + Không cảnh báo chọn nhiều hơn 2 hình: đàn hồi gan
	   ![](https://i.vgy.me/jRIK91.png)
	   ![](https://i.vgy.me/nqlkEU.png)
	   ![](https://i.vgy.me/AJXx7a.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0819.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508191-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508191-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508191-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Diagnose ghi nhật ký message chuẩn HL7 khi gửi chỉ định PACS báo không thành công #385
	- Cập nhật:
		- Ghi log tất cả thao tác lỗi khi gửi dữ liệu sang PACS
		- Folder: Log
		- Mỗi ngày ghi 1 file

		![](https://i.vgy.me/JlTn70.png)
		![](https://i.vgy.me/OMLGJ5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/385
<<<<<<< HEAD

## [v.3.25.0819.0]()
- ✨: Yêu cầu - Diagnose ghi nhật ký message chuẩn HL7 khi gửi chỉ định PACS báo không thành công #385
	- Cập nhật:
		- Ghi log tất cả thao tác lỗi khi gửi dữ liệu sang PACS
		- Folder: Log
		- Mỗi ngày ghi 1 file

		![](https://i.vgy.me/JlTn70.png)
		![](https://i.vgy.me/OMLGJ5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/385
=======

## [v.3.25.0818.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508180-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung thao tác hỗ trợ kết nối PACS Savina (tại BV YHCT Cần Thơ). Lấy bổ sung lời dặn.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/422

## [v.3.25.0815.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32508150-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose: Không chỉnh được kết quả CLS điện tim, điện não, lưu huyết đồ (tham số chukydtdn = 2)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/444

![](https://i.vgy.me/LUJZCv.gif)

## [v.3.25.0730.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507301-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507301-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507301-NasDHSolutions.json)</sup></sup></sub>

- ✨: Yêu cầu - Bổ sung chức năng [Tra cứu lịch sử CĐHA/TDCN] #387
![](https://lh3.googleusercontent.com/pw/AP1GczOvF9VGgbCTvC2yLI7si7AVyIv59VeqMyLFSyI_KYwwShInTLoB9kvduQxI25TvrHo6YApf_CxXTozkcvvzEgaFYmxCcDEStq2U_F_R7Bn3NUy0JWisjbc2swqS9ybCSk9G5mwtXOSJk6LFu17GcbQe=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/387

## [v.3.25.0730.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507300-NasDHSolutions.json)</sup></sup></sub>

- ✨: Yêu cầu - Bổ sung chức năng [Tra cứu lịch sử CĐHA/TDCN] #387
![](https://lh3.googleusercontent.com/pw/AP1GczOSjOukJmQCt2PkuFyRCmTLZLMEsRnSFODugUoq4IH2Y2GlAQ_2J7a-VwQi1bdZtWJSDQzzbrLO1sHZc1Gi6uNpdncSDkUVo6KxNyz3X7V8e501zsZgQ1L2gz_4KDOSKU6X-7rCRWDeWqQbtq5gH2Kz=w1654-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczNxYhXz82kCoskWWoGSoMCNxh7C2-hd6KFuVVsyF4-Xw4Fi0Z5n0RgCj3CefieqPT28p7TMWMsWJxNqq3tvzTHhIir9LbMioFudc6yDU_zw7lN-OJ_K5owmkYmXCtAP4o1sNwL0fabIhIKCP4d9ADYj=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/387

## [v.3.25.0728.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507281-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung thao tác hỗ trợ kết nối PACS Savina (tại BV YHCT Cần Thơ). Sửa lỗi click lấy kết quả từ PACS.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/374

## [v.3.25.0728.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Yêu cầu - Thực hiện kết nối PACS với đối tác Savina - BV YHCT Cần Thơ #374
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/374

## [v.3.25.0714.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507140-NasDHSolutions.json)</sup></sup></sub>
- ✨: YÊU CẦU - DIAGNOSE - Lưu kết quả chậm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/293

- Thay đổi xử lý nếu tham số cks.ketquacls = 0 thì bỏ qua bước kiểm tra chữ ký qua API để tối ưu thời gian lưu kết quả

![](https://live.staticflickr.com/65535/54653258211_4dfcb0ef8e_b.jpg)

## [v.3.25.0710.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	- Cập nhật:
		- Fix Cấu hình số 6. Siêu âm đàn hồi gan, không check cấu hình Sử dụng capture trực tiếp từ chương trình nhưng khi vào form chụp hình lại load chức năng chụp hình trực tiếp từ máy tính, chứ không mở form chọn hình như các CLS khác không có cấu hình đàn hồi gan
		![](https://i.vgy.me/1aaas3.png)

		- Fix lỗi Khi cấu hình số 3. Siêu âm tim kết quả in ngang A4, 2 ảnh, nhập đầu đủ hết tất cả các chỉ số, nhưng có 1 vài chỉ số không load được lên trang kết quả.
		![](https://i.vgy.me/0D4BRA.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0707.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507071-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507071-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507071-NasDHSolutions.json)</sup></sup></sub>

- ✨: YÊU CẦU - DIAGNOSE - Trả kết quả CLS Thu phí chỉ định cho đối tượng BHYT không bắt/áp dụng với 3 tham số ha.sophut...
![](https://lh3.googleusercontent.com/pw/AP1GczM4LtBJREHp0McqkQBbMBLiX_S8FeVPCiILgIyB0l90Q1iNYG7WuaDj2XUAvG9R6rbdZsSmIFYO5jkSy2yBAidDDKs_ukXydNOiEriyKNMKsHE3DgnmAgwXCJ_CjzHBvb_MR_zmzYQOHxXeKTvQGd8E=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/321

## [v.3.25.0707.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32507070-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	- Cập nhật:
	- Trường hợp cấu hình số 3. Siêu âm tim kết quả in ngang A4, 2 ảnh: Có chọn hình, nhưng phiếu kết quả cũng không hiển thị được ảnh
	![](https://i.vgy.me/qKdIqc.png)

	- Đối với cấu hình số 5. 4 ảnh in ở trang thứ 2 A4 vẫn còn lỗi không chọn được 4 hình.	
	![](https://i.vgy.me/5LmjAv.png)
	![](https://i.vgy.me/FToUEY.png)

	- Đàn hồi gan:
	![](https://i.vgy.me/Xitmn4.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0630.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506301-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506301-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506301-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - PK Đông Tây: Diagnose không chỉnh được kết quả CLS cũ #352	
	- Cập nhật thêm 1 số form, cận lâm sạng, theo từng loại Đo mật độ xương, nội soi tai mũi họng, XQuang, điện tim, lưu huyết não, điện não,...
	P/s: fix theo form, theo cận lâm sàng báo lỗi. Còn khi test lại cls khác, form khác là do báo lỗi không đầy đủ, không phải do lỗi phát sinh	
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/352
<<<<<<< HEAD

## [v.3.25.0630.0]()
- 🐛: Lỗi - PK Đông Tây: Diagnose không chỉnh được kết quả CLS cũ #352	
	- Cập nhật thêm 1 số form, cận lâm sạng, theo từng loại Đo mật độ xương, nội soi tai mũi họng, XQuang, điện tim, lưu huyết não, điện não,...
	P/s: fix theo form, theo cận lâm sàng báo lỗi. Còn khi test lại cls khác, form khác là do báo lỗi không đầy đủ, không phải do lỗi phát sinh	
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/352
=======

## [v.3.25.0625.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506252-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506252-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506252-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi - Diagnose: Không lưu được kết quả CLS (phần mềm báo ngày kết quả phải lớn hơn ngày kết quả trước đó). Sửa lỗi ngày kết quả lấy sai khi tham số ha.gioketqua = 1.
![](https://lh3.googleusercontent.com/pw/AP1GczO82U_LEVxd5KSGwB3zkfn_pO3RstspKUKFQNX9EYIwu1ti4wWzExEa6Iugrk2Qof0DSdGBsI0v7ELOlPIO7PaHTmb8kXioe_zTy5jCIiYJfV4JGHtOi7z0sQFQ_W9e9ZfA3RpDzD9K-wrEPHBhYMKp=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/389

## [v.3.25.0625.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506251-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi - Diagnose: Không lưu được kết quả CLS (phần mềm báo ngày kết quả phải lớn hơn ngày kết quả trước đó).
![](https://lh3.googleusercontent.com/pw/AP1GczO82U_LEVxd5KSGwB3zkfn_pO3RstspKUKFQNX9EYIwu1ti4wWzExEa6Iugrk2Qof0DSdGBsI0v7ELOlPIO7PaHTmb8kXioe_zTy5jCIiYJfV4JGHtOi7z0sQFQ_W9e9ZfA3RpDzD9K-wrEPHBhYMKp=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/389

## [v.3.25.0625.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506250-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi - Diagnose: Không lưu được kết quả CLS (phần mềm báo ngày kết quả phải lớn hơn ngày kết quả trước đó).
![](https://lh3.googleusercontent.com/pw/AP1GczN2ukgodDoXGD9aqZ4jaMdpRONtv-SJflrPgLAZRbrdtQSR7R-L7vpyLwZYlsJCY7dGaz4wKBaPzxl6-SHp1mds2iA3KDfBRCsAPN7S1Z7KpRTpSZ5fneGaBs9upe_8w7ibYEa-JZJOXmu1PVeCjzJW=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/389

## [v.3.25.0623.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506231-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506231-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506231-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - DIAGNOSE - Tham số ha.canhbaovuotthoigian =1 không cho lưu kết quả
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/360

- Fix lỗi kiểm tra sai theo tham số ha.sophut_thuchien_toithieu, không cấu hình trả về số phút = 0 vẫn kiểm tra 
- Nếu có cấu hình kiểm tra thì nguyên tắc thời gian thực hiện y lệnh của CLS sau phải cách tối thiếu số phút đã cấu hình so với ngày kết quả của CLS trước.

![](https://live.staticflickr.com/65535/54608812420_8ff74db677_b.jpg)
![](https://live.staticflickr.com/65535/54608525386_0bf30ea8da_b.jpg)

## [v.3.25.0623.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506230-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	- Cập nhật:
		- Fix lỗi không hiển thị hết ảnh trong khung
		![](https://i.vgy.me/6nMERF.png)
		- Fix lỗi không hiển thị ảnh kết quả trang 2
		![](https://i.vgy.me/jmsBHu.png)
		- Fix lỗi không vào thiết kế được với tài khoảng đăng nhập là admin

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0620.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506200-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - PK Đông Tây: Diagnose không chỉnh được kết quả CLS cũ #352
	- Fix: cảnh báo thời gian và cho người dùng lựa chọn có tiếp tục lưu hay không

	![](https://i.vgy.me/4BFtxx.png)
	![](https://i.vgy.me/Ghocqf.png)
	![](https://i.vgy.me/pCg34b.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/352

## [v.3.25.0617.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506170-NasDHSolutions.json)</sup></sup></sub>

- ✨: Ghi nhật ký thao tác Hủy PACS.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/324

## [v.3.25.0612.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506120-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung tham số: cks.ketquacls: Sử dụng phiếu kết quả có chữ ký số bác sĩ (0: không sử dụng; 1: sử dụng).
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0605.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật bổ sung mẫu 1 ảnh và 4 ảnh: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176
	- Cập nhật:
		- Fix lỗi lấy lộn tên bs chỉ định và bs trả kết quả

		![](https://img.upanh.tv/2025/06/05/DebugDiagnose_fzSXF0tMGl.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0605.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32506050-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật bổ sung mẫu 1 ảnh và 4 ảnh: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176
	- Cập nhật:
		- Mở tất cả bệnh viện sử dụng
		- Bổ sung 2 mẫu siêu âm tim: 1 ảnh chung với kết quả và 4 ảnh in ở trang thứ 2

		- Mẫu 1 ảnh:
		![](https://img.upanh.tv/2025/06/05/AbeUBuqkfU.png)
		![](https://img.upanh.tv/2025/06/05/DebugDiagnose_4CgnnL60n1.png)

		- Mẫu 4 ảnh, 2 trang:
		![](https://img.upanh.tv/2025/06/05/DebugDiagnose_4CgnnL60n1.png)
		![](https://img.upanh.tv/2025/06/05/DebugDiagnose_qsLkIIFIBM.png)
		![](https://img.upanh.tv/2025/06/05/DebugDiagnose_KVWjZbMlrc.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0521.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505210-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Đông Hải: Diagnose Mẫu siêu âm tim và siêu âm đàn hồi gan lấy sai ngày kết quả khi xem lại kết quả trên form #299
	- Fix lỗi:
	- Siêu âm tim:
	![](https://i.ibb.co/0V9w4g8z/opera-h5-Yrr-Nwbwi.png)
	![](https://i.ibb.co/JRxPVrtc/n7douqzpv-C.png)

	- Đàn hồi gan:
	![](https://i.ibb.co/1krGnG9/opera-PBy-JYIc9hh.png)
	![](https://i.ibb.co/FLKF3x4G/Debug-Diagnose-j-KCvh-Ko-CQ6.png)


- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/299

## [v.3.25.0520.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505201-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505201-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505201-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	 ✅ Mẫu đã hoàn thành: Siêu âm tim, Đàn hồi gan
		1. Siêu âm tim:
		![](https://i.ibb.co/mVQdk7Zb/Debug-Diagnose-3aay-DEp-FGU.png)
		![](https://i.ibb.co/r2HCFkHk/Debug-Diagnose-Jkl-Owle7-Ws.png)

		2. Đàn hồi gan:
		![](https://i.ibb.co/DgvNbZfy/Debug-Diagnose-1-Fotoc-AAIg.png)
		![](https://i.ibb.co/jZWm4f8W/Debug-Diagnose-JAPajqp-O0-Y.png)

	  - Phạm vị áp dụng: Bệnh viện Quân Dân y tỉnh Đồng Tháp


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176

## [v.3.25.0520.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505200-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - PK Đông Tây: Diagnose không bắt số phút tối thiểu giữa 2 lần trả kết quả của người đọc kết quả khi tài khoản đăng nhập khác tài khoản đọc kết quả
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/301

- Fix lỗi sai mã NV đọc kết quả theo tham số chukydtdn khi kiểm tra số phút tối thiểu cho Điện tim, Điện não
![](https://i.ibb.co/3mscgcLz/f-Dxgp8-Dw5-F.png)
![](https://i.ibb.co/fVB5bVYt/y-Lmf-Hz4-Ac-C.png)

## [v.3.25.0519.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505193-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505193-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505193-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	 ✅ Mẫu đã hoàn thành: XQuang, Điện não, Lưu Huyết Não, Chức Năng Hô Hấp
		1. Xquang:
		![](https://ibb.co/Z6yC506C)
		![](https://ibb.co/W4J5Pmwt)

		2. Điện não:
		![](https://ibb.co/d08JsVkr)
		![](https://ibb.co/1Gtx8MPx)

		3. Lưu Huyết Não:
		![](https://ibb.co/gqDSwPH)
		![](https://ibb.co/Hf3kcY7N)

		4. Chức Năng Hô Hấp:
		![](https://ibb.co/C5T89xwH)
		![](https://i.ibb.co/q3NGDc5L/Debug-Diagnose-5-R35-ZZYGm-G.png)

	  ❌  Mẫu chưa hoàn thành, trễ hạn: Siêu âm tim, Đàn hồi gan

	  - Phạm vị áp dụng: Bệnh viện Quân Dân y tỉnh Đồng Tháp
	  - Cần nhóm triển khai hỗ trợ 1 bộ dữ liệu hoàn chỉnh cho các biểu mẫu trên để thuận tiện cho việc TEST

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/176
<<<<<<< HEAD

## [v.3.25.0519.2]()
- ✨: Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32 2023 TT-BYT. #176
	 ✅ Mẫu đã hoàn thành: XQuang, Điện não, Lưu Huyết Não, Chức Năng Hô Hấp
		1. Xquang:
		![](https://ibb.co/Z6yC506C)
		![](https://ibb.co/W4J5Pmwt)

		2. Điện não:
		![](https://ibb.co/d08JsVkr)
		![](https://ibb.co/1Gtx8MPx)

		3. Lưu Huyết Não:
		![](https://ibb.co/gqDSwPH)
		![](https://ibb.co/Hf3kcY7N)

		4. Chức Năng Hô Hấp:
		![](https://ibb.co/C5T89xwH)
		![](https://i.ibb.co/q3NGDc5L/Debug-Diagnose-5-R35-ZZYGm-G.png)

	  ❌  Mẫu chưa hoàn thành, trễ hạn: Siêu âm tim, Đàn hồi gan

	  - Phạm vị áp dụng: Bệnh viện Quân Dân y tỉnh Đồng Tháp
	  - Cần nhóm triển khai hỗ trợ 1 bộ dữ liệu hoàn chỉnh cho các biểu mẫu trên để thuận tiện cho việc TEST

## [v.3.25.0519.1]()
- ✨:Yêu cầu - Tự thiết kế một số mẫu đối với Thông tư số 32/2023/TT-BYT. #176
	 ✅ Mẫu đã hoàn thành: XQuang, Điện não, Lưu Huyết Não, Chức Năng Hô Hấp
		1. Xquang:
		![](https://ibb.co/Z6yC506C)
		![](https://ibb.co/W4J5Pmwt)

		2. Điện não:
		![](https://ibb.co/d08JsVkr)
		![](https://ibb.co/1Gtx8MPx)

		3. Lưu Huyết Não:
		![](https://ibb.co/gqDSwPH)
		![](https://ibb.co/Hf3kcY7N)

		4. Chức Năng Hô Hấp:
		![](https://ibb.co/C5T89xwH)
		![](https://i.ibb.co/q3NGDc5L/Debug-Diagnose-5-R35-ZZYGm-G.png)

	  ❌  Mẫu chưa hoàn thành, trễ hạn: Siêu âm tim, Đàn hồi gan

	  - Phạm vị áp dụng: Bệnh viện Quân Dân y tỉnh Đồng Tháp
	  - Cần nhóm triển khai hỗ trợ 1 bộ dữ liệu hoàn chỉnh cho các biểu mẫu trên để thuận tiện cho việc TEST

## [v.3.25.0519.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505190-NasDHSolutions.json)</sup></sup></sub>

- ✨: Sổ chẩn đoán hình ảnh: điều chỉnh cột [Ngày thực hiện] thành [Ngày đọc kết quả].
![](https://i.ibb.co/R4g7jgMc/image.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/240

## [v.3.25.0517.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505170-NasDHSolutions.json)</sup></sup></sub>

- ✨: Sổ chẩn đoán hình ảnh bổ sung thêm cột Giờ thực hiện y lệnh và Người thực hiện Y Lệnh
![](https://i.postimg.cc/dVZ7mQRg/image.png)
![](https://i.postimg.cc/VvNvSzLG/image.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/240

## [v.3.25.0506.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32505060-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mô tả thêm bắt thời gian thực hiện theo Kho CĐHA #22
	- Cập nhật:
		+ Nếu [Ngày thực hiện y lệnh đã chọn trên form] <= pskhamha.ngaycd (lấy max theo manv trả kết quả) => Cảnh báo và không cho lưu
		+ Chụp CT:
		![](https://i.imgur.com/KdFcrnT.png)
		![](https://i.imgur.com/Y5dKZQk.png)

		+ Siêu âm:
		![](https://i.imgur.com/SAYvfcR.png)

		+ Nếu [pskhamha.ngaycd + sophutthuchien] > [Ngày trả kết quả trên form] => Cảnh báo và không cho lưu
		+ Điện tim
		![](https://i.imgur.com/HlCqgkG.png)
		+ XQ:
		![](https://i.imgur.com/K3t1JlJ.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/22

## [v.3.25.0427.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504270-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi không gửi được kết quả CT và XQ sang hệ thống PACS (BV Tâm Phúc).
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0426.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504260-NasDHSolutions.json)</sup></sup></sub>

- ✨: Kết nối PACS Tâm Phúc. Hỗ trợ đẩy kết quả từ HIS => PACS. Thêm mới: đẩy khi status = 4; Hiệu chỉnh: đẩy khi status = 0.
![](https://i.imgur.com/juJyV0k.png)
- 🐛: Sửa lỗi phiếu XQ lỗi hiển thị mô tả (BV Tâm Phúc).
![](https://i.imgur.com/CpcLhGL.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0425.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504251-NasDHSolutions.json)</sup></sup></sub>

- ✨: Hỗ trợ chuyển đổi nội dung HTML sang RTF các kết quả từ hệ thống PACS (BV Tâm Phúc).
![](https://i.imgur.com/HooVQH2.png)
![](https://i.imgur.com/Or90XUp.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0425.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504250-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi phiếu chụp CT không hiển thị được mô tả.
![](https://i.imgur.com/bfmP7Z5.png)
- ✨: Form thực hiện X-Quang và Chụp CT: Bổ sung nút load kết quả từ hệ thống PACS (BV Tâm Phúc).
![](https://i.imgur.com/LvcaSLK.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0424.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504241-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi siêu âm tim khi cấu hình siêu âm 1 ảnh chung với kết quả sẽ không ký số được.
![](https://i.imgur.com/e7Qdf56.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0424.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504240-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi `Phiếu siêu âm tim (trang 2)` chưa ký số được.
![](https://i.imgur.com/K9X6qrS.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0422.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504222-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504222-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504222-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi form thực hiện Nội soi TMH khi tham số `ha.sudungmotabenhly = 3`.
![](https://i.imgur.com/EHeoSt5.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0422.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504221-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504221-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504221-NasDHSolutions.json)</sup></sup></sub>

- ✨: BV Tâm Phúc: Bổ sung chức năng lưu kết quả chụp CT gửi PACS theo trạng thái giống với XQ.
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0422.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504220-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung áp dụng tham số `ha.sudungmotabenhly=3` đối với Chụp CT.
![](https://i.imgur.com/9RaaLZv.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0418.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504182-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504182-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504182-NasDHSolutions.json)</sup></sup></sub>
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
	+ Cập nhật:
		- Gửi chỉ định theo mô tả:
		![](https://i.imgur.com/noZhkDI.png)
		Một số thao tác gửi:
		![](https://i.imgur.com/M7P51EH.gif)

		- Cập nhật chỉ định:
		+ XQ:
		![](https://i.imgur.com/zmyQKoI.png)
		![](https://i.imgur.com/pgSaLCi.png)

		+ CT:
		![](https://i.imgur.com/stj9XKS.png)

		Hệ thống PACS phản hồi khi nhận thông tin
		![](https://i.imgur.com/spoERCQ.png)
		![](https://i.imgur.com/eOkWkOS.png)

		+ Điện não:
		![](https://i.imgur.com/hRPG1WQ.png)
		![](https://i.imgur.com/ZlVvyly.png)

		+ Không hiển thị link sau khi thực hiện tác lưu kết quả

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0418.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504181-NasDHSolutions.json)</sup></sup></sub>
- ✨: update

## [v.3.25.0418.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504180-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng ký số đối với các mẫu kết quả Chẩn đoán hình ảnh/Thăm dò chức năng.
![](https://i.imgur.com/3qXmOni.png)
![](https://i.imgur.com/bfmwrwi.png)
![](https://i.imgur.com/5Hu4B4W.png)
![](https://i.imgur.com/Ldd8DUQ.png)
![](https://i.imgur.com/c7At5JC.png)
![](https://i.imgur.com/SKgCO4g.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0415.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504151-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504151-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504151-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: Sổ chẩn đoán hình ảnh không thể hiện kết quả loại CLS chức năng hô hấp.
![](https://i.imgur.com/eL343F5.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/229

## [v.3.25.0415.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504150-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: Sổ chẩn đoán hình ảnh không thể hiện kết quả loại CLS chức năng hô hấp.
![](https://i.imgur.com/eL343F5.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/229

## [v.3.25.0409.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504093-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504093-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504093-NasDHSolutions.json)</sup></sup></sub>
- ✨: Kết nối PACS BV Tâm Phúc: Cập nhật gửi chỉ định và gửi kết quả sai trường chẩn đoán
	 
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0409.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504092-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504092-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504092-NasDHSolutions.json)</sup></sup></sub>

- ✨: Kết nối PACS BV Tâm Phúc: Bổ sung hàm lấy liên kết PatientPortalDirectLink tạo QRCode trên phiếu kết quả.
![](https://i.imgur.com/7mYHwJe.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/156

## [v.3.25.0409.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504091-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504091-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504091-NasDHSolutions.json)</sup></sup></sub>
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
	- Cập nhật: BV Tâm Phúc lấy giá trị theo tham số khi kết nối PACS:
		+ ip_server_pacs
		+ ha.secret_key
		+ ha.server_link_viewer
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
<<<<<<< HEAD

## [v.3.25.0409.0]()
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
	- Cập nhật: BV Tâm Phúc lấy giá trị theo tham số khi kết nối PACS:
		+ ip_server_pacs
		+ ha.secret_key
		+ ha.server_link_viewer
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
=======

## [v.3.25.0408.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504080-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - DIAGNOSE - Form trả kết quả nội soi nút Mở hình ảnh bấm vào không hiển thị form
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/211

![](https://i.imgur.com/LZXo20m.gif)

## [v.3.25.0407.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504070-NasDHSolutions.json)</sup></sup></sub>

- ✨: Hiển thị kết quả `Phiếu XQ, Phiếu chụp CT` bổ sung `QRCode` từ `link viewer` ca chụp từ hệ thống PACS (Bệnh viện Tâm Phúc).
Phiếu X-Quang:
![](https://i.imgur.com/HryxIMU.png)

Phiếu Chụp CT:
![](https://i.imgur.com/21cOI3I.png)
![](https://i.imgur.com/CHwE19J.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/156

## [v.3.25.0406.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504060-NasDHSolutions.json)</sup></sup></sub>

- ✨: `Phiếu XQ, Phiếu chụp CT` bổ sung `QRCode` từ `link viewer` ca chụp từ hệ thống PACS (Bệnh viện Tâm Phúc).
Phiếu X-Quang:
![](https://i.imgur.com/6DbvFE8.png)

Phiếu Chụp CT:
![](https://i.imgur.com/21cOI3I.png)
![](https://i.imgur.com/CHwE19J.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/156

## [v.3.25.0404.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504042-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504042-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504042-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi: Gửi kết quả Xquang, City từ HIS sangPACS chưa được #203
	- Cập nhật: gửi kết quả mô tả và kết luận, có thể xuống dòng

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/203
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0404.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504041-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504041-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504041-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi: Gửi kết quả Xquang, City từ HIS sangPACS chưa được #203
	- Cập nhật: gửi chỉ định và kết quả với tiếng Việt có dấu (bản trước gửi không dấu)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/203
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0404.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi: Gửi kết quả Xquang, City từ HIS sangPACS chưa được #203
	- Cập nhật: gửi chỉ định và kết quả với tiếng Việt có dấu (bản trước gửi không dấu)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/203
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0403.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504031-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504031-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504031-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi: Gửi kết quả Xquang, City từ HIS sangPACS chưa được #203
	- Cập nhật:
		
		+ Khi lưu XQ mà chưa chụp bên PACS.
		![](https://i.imgur.com/XVvhLy6.gif)
		+ Lưu kết quả XQ, sau khi đã chụp bên PACS
		![](https://i.imgur.com/nNK4UAt.gif)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/203
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
<<<<<<< HEAD

## [v.3.25.0403.0]()
- 🐛: Lỗi: Gửi kết quả Xquang, City từ HIS sangPACS chưa được #203
	- Cập nhật:
		
		+ Khi lưu XQ mà chưa chụp bên PACS.
		![](https://i.imgur.com/XVvhLy6.gif)
		+ Lưu kết quả XQ, sau khi đã chụp bên PACS
		![](https://i.imgur.com/nNK4UAt.gif)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/203
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
=======

## [v.3.25.0402.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32504020-NasDHSolutions.json)</sup></sup></sub>

- ✨: Số chẩn đoán hình ảnh bổ sung cột `Tên phim` và `Số lượng`.
![](https://i.imgur.com/GaEjoSC.png)

- ✨: Báo cáo Sử dụng phim X-Quang => Theo tên bệnh nhân: bổ sung cột `Mã liên kết`, `Tên cận lâm sàng` và `Ngày chỉ định`.
![](https://i.imgur.com/yjJccfX.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/167

## [v.3.25.0326.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503261-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503261-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503261-NasDHSolutions.json)</sup></sup></sub>
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
	+ Cập nhật:
	Đã TEST gửi và hủy dữ liệu:
	![](https://i.imgur.com/yxue5nA.jpeg)

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0326.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503260-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - DIAGNOSE - Hủy kết quả báo lỗi
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/179

![](https://i.imgur.com/L6eKVc3.gif)

## [v.3.25.0324.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503240-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose Trả kết quả Chức năng hô hấp (BV Lấp Vò)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/162

- Fix lỗi giao diện sai vị trí control Người thực hiện y lệnh
![](https://i.imgur.com/h4iqapn.png)

## [v.3.25.0322.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503220-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Cập nhật API kết nối PACS Bệnh viện Tâm Phúc #102
	 Fix lỗi: đã hủy gửi PACS, trên HIS vẫn chưa hủy
	 ![](https://i.imgur.com/IesblRM.gif)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/102

## [v.3.25.0319.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503190-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Cập nhật API kết nối PACS Bệnh viện Tâm Phúc
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/102 

- Bổ sung kiểm tra kết quả và đưa vào mô tả bệnh lý và kết luận từ PACS nếu có 
- Mô tả bệnh lý áp dụng tham số ha.sudungmotabenhly = 0 và ha.sudungchitietmtbl = 0
![](https://i.imgur.com/6McIs4t.png)
![](https://i.imgur.com/0ZuEREy.gif)

## [v.3.25.0311.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503113-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503113-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503113-NasDHSolutions.json)</sup></sup></sub>

- ✨: Chức năng ghi nhận dữ liệu phân luồng kết quả theo tham số `phanluong.ketqua`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/109

## [v.3.25.0311.2]()

- ✨: Chức năng ghi nhận dữ liệu phân luồng kết quả theo tham số `phanluong.ketqua`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/109

## [v.3.25.0311.1]()

- ✨: Chức năng ghi nhận dữ liệu phân luồng kết quả theo tham số `phanluong.ketqua`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/109
<<<<<<< HEAD

## [v.3.25.0311.0]()

- ✨: Chức năng ghi nhận dữ liệu phân luồng kết quả theo tham số `phanluong.ketqua`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/109
=======

## [v.3.25.0310.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32503100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Diagnose hỗ trợ chụp ảnh và trả kết quả cùng một Form
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/51

![](https://i.imgur.com/TUd6X5P.png)

![](https://i.imgur.com/HjzxlgJ.png)
<<<<<<< HEAD

## [v.3.25.0310.0]()
- ✨: Yêu cầu: Diagnose hỗ trợ chụp ảnh và trả kết quả cùng một Form
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/51

![](https://i.imgur.com/TUd6X5P.png)
![](https://i.imgur.com/HjzxlgJ.png)
=======

## [v.3.25.0228.5]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502285-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502285-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502285-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose trả kết quả điện tim (PK Sadec) #104
	Fix lỗi khi lưu lần 2:
	![](https://i.imgur.com/I39pFgj.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/104

## [v.3.25.0228.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502284-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502284-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502284-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose trả kết quả điện tim (PK Sadec) #104
	Fix lỗi khi lưu lần 2:
	![](https://i.imgur.com/I39pFgj.png)

## [v.3.25.0228.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502283-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502283-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502283-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose trả kết quả điện tim (PK Sadec) #104
	Fix lỗi khi lưu lần 2:
	![](https://i.imgur.com/I39pFgj.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/104

## [v.3.25.0228.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502282-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502282-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502282-NasDHSolutions.json)</sup></sup></sub>
- ✨: Update test đồng bộ dll

## [v.3.25.0228.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502281-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Diagnose trả kết quả điện tim (PK Sadec) #104
	Fix lỗi khi lưu:
	![](https://i.imgur.com/mRtJyJV.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/104
<<<<<<< HEAD

## [v.3.25.0228.0]()
- 🐛: Lỗi - Diagnose trả kết quả điện tim (PK Sadec) #104
	Fix lỗi khi lưu:
	![](https://i.imgur.com/mRtJyJV.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/104
=======

## [v.3.25.0221.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Form [Danh sách bệnh nhân] thực hiện cận lâm sàng không thể hiện được AssignCode đã gửi PACS.
![](https://i.imgur.com/MnrYYu8.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/85

## [v.3.25.0211.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502112-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502112-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502112-NasDHSolutions.json)</sup></sup></sub>
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
		Cấu hình sử dụng PACS (BV Tâm Phúc)
			TEST:

			Server: 192.168.50.79
			Data: pacs_tamphuc
			Port: 5432

			- Cấu hình tham số:
			ip_server_pacs = http://115.78.238.215:8081

			- Cấp quyền sử dụng:
			![](https://i.imgur.com/drlC4xD.png)
			Lưu ý: không cấp quyền sẽ không thấy được chức năng

			- Gửi PACS:

			![](https://i.imgur.com/vdSLpt6.png)

			- Hủy gửi PACS:

			![](https://i.imgur.com/zlV3Q3K.png)

			- Xem kết quả từ PACS:

			![](https://i.imgur.com/hu3f3tx.png)
			![](https://i.imgur.com/hnHS9ud.png)

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6

## [v.3.25.0211.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502111-NasDHSolutions.json)</sup></sup></sub>
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
		Cấu hình sử dụng PACS (BV Tâm Phúc)
			TEST:

			Server: 192.168.50.79
			Data: pacs_tamphuc
			Port: 5432

			- Cấu hình tham số:
			ip_server_pacs = http://115.78.238.215:8081

			- Cấp quyền sử dụng:
			![](https://i.imgur.com/drlC4xD.png)
			Lưu ý: không cấp quyền sẽ không thấy được chức năng

			- Gửi PACS:

			![](https://i.imgur.com/vdSLpt6.png)

			- Hủy gửi PACS:

			![](https://i.imgur.com/zlV3Q3K.png)

			- Xem kết quả từ PACS:

			![](https://i.imgur.com/hu3f3tx.png)
			![](https://i.imgur.com/hnHS9ud.png)

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
<<<<<<< HEAD

## [v.3.25.0211.0]()
- ✨: PACS - Kết nối PACS (BV TÂM PHÚC) #6
		Cấu hình sử dụng PACS (BV Tâm Phúc)
			TEST:

			Server: 192.168.50.79
			Data: pacs_tamphuc
			Port: 5432

			- Cấu hình tham số:
			ip_server_pacs = http://115.78.238.215:8081

			- Cấp quyền sử dụng:
			![](https://i.imgur.com/drlC4xD.png)
			Lưu ý: không cấp quyền sẽ không thấy được chức năng

			- Gửi PACS:

			![](https://i.imgur.com/vdSLpt6.png)

			- Hủy gửi PACS:

			![](https://i.imgur.com/zlV3Q3K.png)

			- Xem kết quả từ PACS:

			![](https://i.imgur.com/hu3f3tx.png)
			![](https://i.imgur.com/hnHS9ud.png)

- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/6
=======

## [v.3.25.0209.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32502090-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kết nối PACS (Vĩnh Phát) BV Nhi Đồng Cần Thơ.
![image](/attachments/65d4edf1-1252-4dcf-906e-dd739c8d5091)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/41

## [v.3.25.0123.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501230-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kết nối PACS (xuất thông tin chỉ định Excel) PK Phương Nam. Theo mô tả: [CHUC-NANG-RIENG/PACs-Excel-PK-Phuong-Nam.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CHUC-NANG-RIENG/PACs-Excel-PK-Phuong-Nam.md)
![](https://i.imgur.com/t726BGn.png)
![](https://i.imgur.com/VDDiC7h.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/7

## [v.3.25.0113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Thực hiện - Tích hợp vào hệ thống cấp key của HĐĐT - (dh-issue/YEUCAU/#18)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/18

## [v.3.25.0110.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501100-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Form `[Phân luồng]`: Sửa lỗi chưa ưu tiên phân vào phòng cấu hình cls có số BN ít nhất.
![](https://i.imgur.com/IJemxHt.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0109.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501090-NasDHSolutions.json)</sup></sup></sub>

- ✨: Thay đổi cách xác định phòng sau khi quét mã vạch tại form `[Phân luồng]`.
![](https://i.imgur.com/jodURPL.png)
![](https://i.imgur.com/FCYRv1P.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0105.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501050-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi form cấu hình máy mặc định load sai cận lâm sàng.
![](https://i.imgur.com/lTnrgpr.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/26

## [v.3.25.0104.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501040-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng cấu hình khu vực.
![](https://i.imgur.com/m5syUaX.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0101.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32501010-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung menu báo cáo `Sổ TT/PT TTYT Trà Cú (84006)`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/2

## [v.3.24.1229.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412291-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412291-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412291-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng `[Phân luồng]` và `[Gọi bệnh]`.
![image](https://github.com/user-attachments/assets/60fd738e-4d2f-412e-9136-db318e87936c)
![image](https://github.com/user-attachments/assets/866a802a-0ee4-4dae-8200-449ae5f4d2f6)
- ☑: https://github.com/dhhiswork/DuAn/issues/7
<<<<<<< HEAD

## [v.3.24.1229.0]()

- ✨: Bổ sung chức năng `[Phân luồng]` và `[Gọi bệnh]`.
![image](https://github.com/user-attachments/assets/60fd738e-4d2f-412e-9136-db318e87936c)
![image](https://github.com/user-attachments/assets/866a802a-0ee4-4dae-8200-449ae5f4d2f6)
- ☑: https://github.com/dhhiswork/DuAn/issues/7
=======

## [v.3.24.1227.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412270-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã chính thức 96176 Phòng khám đa khoa Y Đức Sài Gòn - YEUCAU
- ☑: https://i.dh-his.com/test/YEUCAU/issues/4

## [v.3.24.1226.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412260-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng lập phiếu TT/PT cho `TTYT huyện Trà Cú (mabv: 84006)`.
- ☑: https://github.com/dhhiswork/YeuCau/issues/66

## [v.3.24.1220.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412200-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã tạm 96151 Phòng khám đa khoa Sài Gòn Y Đức ·
- ☑: https://github.com/dhhiswork/YeuCau/issues/60

## [v.3.24.1218.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412180-NasDHSolutions.json)</sup></sup></sub>

- ✨: Yêu cầu - BV Sa Đéc: Tham số cảnh báo hoặc chặn lưu phiếu TT/PT khi trùng giờ ekip
- ✨: Bổ sung chức năng theo tham số `ttpt.canhbaothoigiantrungekip`, thực hiện theo [Mô tả Kiểm tra thời gian kết quả HA-CN-TT-PT](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20Ki%E1%BB%83m%20tra%20th%E1%BB%9Di%20gian%20k%E1%BA%BFt%20qu%E1%BA%A3%20HA-CN-TT-PT.md)
![](https://i.imgur.com/ueoTt9U.png) 
![](https://i.imgur.com/FKxq39J.png) 
![](https://i.imgur.com/t6ZrN6h.png) 
![](https://i.imgur.com/FkCUyX0.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/55

## [v.3.24.1212.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412120-NasDHSolutions.json)</sup></sup></sub>

- ✨: Form lập phiếu TT/PT: Bổ sung điều kiện chỉ áp dụng đối với BHYT và loại bỏ TT/PT trùng thời gian thực hiện.
- ☑: https://github.com/dhhiswork/YeuCau/issues/38

## [v.3.24.1210.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412100-NasDHSolutions.json)</sup></sup></sub>

- ✨: Form thực hiện TT/PT: Bổ sung điều kiện kiểm tra cận lâm sàng có bắt trùng thời gian thực hiện. Nếu `dmcls.trungekkip_thuchien <> 1` thì tiến hành kiểm tra trùng thời gian thực hiện của Ekip.
- ☑: https://github.com/dhhiswork/YeuCau/issues/38

## [v.3.24.1205.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412053-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412053-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412053-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Prescription chỉnh sửa thông tin hồ sơ thanh toán BHYT đã in phiếu thanh toán và đã mở khóa ![](https://i.imgur.com/10OMhGk.png) ![](https://i.imgur.com/ZD0V7HS.png)
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

## [v.3.24.1205.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412052-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412052-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412052-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Prescription chỉnh sửa thông tin hồ sơ thanh toán BHYT đã in phiếu thanh toán và đã mở khóa ![](https://i.imgur.com/10OMhGk.png) ![](https://i.imgur.com/ZD0V7HS.png)
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

## [v.3.24.1205.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - mở khoá không xoá giờ kết thúc khám không cho thêm chi phí mới
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

- không hợp lệ > chặn
![](https://i.imgur.com/10OMhGk.png)
- hợp lệ cho phép lưu
![](https://i.imgur.com/ZD0V7HS.png)

## [v.3.24.1205.0]()
- ✨: Yêu cầu - mở khoá không xoá giờ kết thúc khám ràng buộc giờ kết quả không được lớn hơn giờ kết thúc khám
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

![](https://i.imgur.com/S6NSQl7.png)
![](https://i.imgur.com/xcB7PVx.png)
![](https://i.imgur.com/Dt31V89.png)

- Cho phép lưu nếu thời gian hợp lệ
![](https://i.imgur.com/18lDKhL.png)

## [v.3.24.1202.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412020-NasDHSolutions.json)</sup></sup></sub>

- ✨: Kiểm soát thời gian thực hiện TT/PT đối với nhân viên trong EkipPT khi lưu phiếu TT/PT.
![image](https://github.com/user-attachments/assets/80e59624-fb40-4de0-829b-6ac219001493)
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/6

## [v.3.24.1201.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32412010-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi khi lưu kết quả (kết nối PACS Vĩnh Phát).
- ☑: https://github.com/dhhiswork/Loi/issues/54

## [v.3.24.1128.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kiểm tra theo tham số `ha.ketluan`: Cảnh báo/Chặn nội dung kết luận rỗng khi thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng.
![image](https://github.com/user-attachments/assets/46005cb5-a344-4fb3-8bde-5a8f2138db7b)
![image](https://github.com/user-attachments/assets/0c38eab7-d5fc-49b2-b173-9181aa65e013)
- ☑: https://github.com/dhhiswork/YeuCau/issues/17

## [v.3.24.1120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411200-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: Khi lưu kết quả phát sinh lỗi (BV Ung Bướu Cần Thơ) do lấy kết quả từ hệ thống PACS (Vĩnh Phát).
- ☑: https://github.com/dhhiswork/Loi/issues/12

## [v.3.24.1115.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411150-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung hạn sử dụng chức năng PACS BV Ung Bướu: 31/12/2024.

## [v.3.24.1103.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411031-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411031-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411031-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kiểm tra thời gian khóa thực hiện (đối với nhân viên thực hiện y lệnh, bắt tương tự đối với bác sĩ trả kết quả).
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/21

## [v.3.24.1103.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411030-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411030-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411030-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kiểm tra thời gian khóa thực hiện (đối với nhân viên thực hiện y lệnh, bắt tương tự đối với bác sĩ trả kết quả).
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/21

## [v.3.24.1102.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411020-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411020-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32411020-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng kiểm tra thời gian khóa thực hiện (đối với nhân viên thực hiện y lệnh, bắt tương tự đối với bác sĩ trả kết quả).
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/21

## [v.3.24.1031.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410310-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410310-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410310-NasDHSolutions.json)</sup></sup></sub>

- ✨: Form danh mục bệnh lý: Canh giữa tool format (phù hợp với các control còn lại trên form).
![image](https://github.com/user-attachments/assets/67ea95f4-2e95-46d4-805e-4917df917542)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/9

## [v.3.24.1030.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410300-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410300-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410300-NasDHSolutions.json)</sup></sup></sub>

- ✨: Danh mục bệnh lý: bổ sung format (định dang cỡ chữ, màu, in đậm, in nghiêng, ...) cho kết luận, lời dặn.
![image](https://github.com/user-attachments/assets/3586d9a0-10fb-47ac-a2e2-bccf0ab0261b)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/9

## [v.3.24.1028.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410281-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410281-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410281-NasDHSolutions.json)</sup></sup></sub>


- ✨: Danh mục bệnh lý: bổ sung format (định dang cỡ chữ, màu, in đậm, in nghiêng, ...) cho kết luận, lời dặn.
![image](https://github.com/user-attachments/assets/3586d9a0-10fb-47ac-a2e2-bccf0ab0261b)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/9

## [v.3.24.1028.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-NasDHSolutions.json)</sup></sup></sub> <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDiagnoseexe%2F32410280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Danh mục bệnh lý: bổ sung format (định dang cỡ chữ, màu, in đậm, in nghiêng, ...) cho kết luận, lời dặn.
![image](https://github.com/user-attachments/assets/3586d9a0-10fb-47ac-a2e2-bccf0ab0261b)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/9

## [v.3.24.1014.0]()

- 🐛: Sửa lỗi: Mất Menu Tool chỉnh định dạng font chữ khi sử dụng Mô tả bệnh lý (không chỉnh được định dạng kết luận và lời dặn). ![image](https://github.com/user-attachments/assets/7e675c9c-26f4-4f8c-8673-7cc02f4278b1)
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/69

## [v.3.24.1012.0]()

- ✨: Bổ sung chức năng kết nối PACS (Cty Vĩnh Phát) BV Ung Bướu Cần Thơ. ![image](https://github.com/user-attachments/assets/efcd4749-23a9-4c6f-bb1c-ea2a80cd535c)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/657

## [v.3.24.1001.0]()

- 🐛: Sửa lỗi: Không hiển thị tiền công ekip PT/TT tại form lập phiếu TT/PT.
- ✨: Hiển thị mã loại PT tại cột TT/PT trên danh sách thực hiện CLS.
- ✨: Khóa các nút thêm nhân viên thực hiện Ekip TT/PT sau khi lập xong phiếu TT/PT.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/68

## [v.3.24.0930.0]()

- 🐛: Sửa các lỗi tổng hợp phiếu TT/PT. ![image](https://github.com/user-attachments/assets/56ff022e-af64-48f9-89d1-a9778429cb96)
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/68

## [v.3.24.0926.0]()

- 🐛: Sửa lỗi thực hiện Thủ thuật/Phẫu thuật.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/68

## [v.3.24.0923.0]()

- 🐛: Sửa lỗi: mất chức năng lập phiếu thủ thuật BV Tim Mạch CT.
- 🐛: Sửa lỗi: các form thực hiện cận lâm sàng load thiếu bệnh lý.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/68
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/67

## [v.3.24.0920.2]()

- 🐛: Sửa lỗi: mất chức năng lập phiếu thủ thuật BV Tim Mạch CT.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/68

## [v.3.24.0920.1]()

- 🐛: Sửa lỗi: các form thực hiện cận lâm sàng load thiếu bệnh lý.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/67

## [v.3.24.0920.0]()

- 🐛: Sửa lỗi: Load thiếu bệnh lý tại form [Chi tiết mô tả bệnh lý].
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/67

## [v.3.24.0918.0]()

- 🐛: Sửa lỗi load thiếu bệnh lý đối với danh mục mô tả bệnh lý. ![image](https://github.com/user-attachments/assets/df15fab3-ffa9-45e6-bc12-8ae40cfe6b46)
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/67

## [v.3.24.0829.0]()

- 🐛: Sửa lỗi không chọn được font mô tả khi sử dụng tham số `ha.sudungmotabenhly = 1`.
- 🐛: Lưu ý: do sử dụng tham số `ha.sudungmotabenhly = 1`, nên tại phiếu tự thiết kế phải kéo lại parameter mota mới trở lại phiếu kết quả (parameter cũ hỗ trợ Rtf, nên không còn phù hợp) ![image](https://github.com/user-attachments/assets/071e32e8-f2f4-4b3f-a9f4-0acebc40ab3f)
- 🐛: Với parameter mota mới, nhớ chọn thuộc tính `Multiline = Yes`: ![image](https://github.com/user-attachments/assets/5262feb0-3243-4f9f-a43b-c8cc1d85498e)
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/66

## [v.3.24.0822.0]()

- 🐛: Sửa lỗi không chặn hủy kết quả khi áp dụng tham số thuchiencls_phieu01.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/65

## [v.3.24.0821.0]()

- 🐛: Sửa lỗi không chọn được bệnh lý khi điều chỉnh kết quả.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/65

## [v.3.24.0814.0]()

- ✨: Bổ sung tùy chọn `Xóa toàn bộ ảnh từ thiết bị capture khác sau mỗi ca được thực hiện` tại form cấu hình thực hiện cận lâm sàng.
- ✨: Thực hiện kiểm soát tại các form thực hiện theo tùy chọn `Xóa toàn bộ ảnh từ thiết bị capture khác sau mỗi ca được thực hiện`.
![image](https://github.com/user-attachments/assets/cb2808d4-60fc-4c92-80e7-6d0b51b6f32f)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/593

## [v.3.24.0809.0]()

- 🐛: Sửa lỗi khi tài khoản đăng nhập có quyền thực hiện (không có quyền đọc kết quả) KHÔNG có tên trong danh sách chọn nhân viên thực hiện.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/64

## [v.3.24.0804.0]()

- ✨: Thay đổi kiểm tra số phút tối thiểu để trả kết quả từ lần trả kết quả gần nhất của người đọc kết quả theo loại cận lâm sàng theo tham số `ha.sophut_thuchien_toithieu` từ số sang chuỗi. ![image](https://github.com/user-attachments/assets/eb7e58ae-f9f6-4730-888f-7caf8c72b0ac)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/62
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/59

## [v.3.24.0802.0]()

- 🐛: Sửa lỗi không load phim CT khi thực hiện.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/63

## [v.3.24.0731.0]()

- ✨: Bổ sung kiểm tra [thời gian thực hiện y lệnh] và [thời gian trả kết quả] theo [Mô tả Kiểm tra thời gian Thực hiện y lệnh/Trả kết quả đối với Chẩn đoán hình ảnh/Thăm dò chức năng](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20Ki%E1%BB%83m%20tra%20th%E1%BB%9Di%20gian%20th%E1%BB%B1c%20hi%E1%BB%87n%20y%20l%E1%BB%87nh-tr%E1%BA%A3%20k%E1%BA%BFt%20qu%E1%BA%A3%20Ch%E1%BA%A9n%20%C4%91o%C3%A1n%20h%C3%ACnh%20%E1%BA%A3nh%20-%20Th%C4%83m%20d%C3%B2%20ch%E1%BB%A9c%20n%C4%83ng.md)
![image](https://github.com/user-attachments/assets/11231f7b-b8b5-4149-83de-cbc9c2ddd36d)
![image](https://github.com/user-attachments/assets/248775ea-3422-4d1d-b44c-2282e4fed0ad)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/555
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/527

## [v.3.24.0728.0]()

- ✨: Bổ sung chức năng cấu hình người thực hiện. ![image](https://github.com/user-attachments/assets/2ea15dca-8ed8-417b-b8cd-3002385e1289). 
- ✨: Bổ sung chức năng chọn người thực hiện tại các form trả kết quả. ![image](https://github.com/user-attachments/assets/32ce337f-8acc-4cd2-9fcb-33fdea37d557)
- ✨: Ghi nhận giá trị `chidinhcls.nguoi_thuc_hien` khi thực hiện cận lâm sàng.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/539

## [v.3.24.0722.0]()

- 🐛: Sửa lỗi không tìm thấy cột maphim khi vào form thực hiện XQuang. ![image](https://github.com/user-attachments/assets/9ba4c178-732e-4fa3-adaa-4a1dde8d1e55)
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/62

## [v.3.24.0721.0]()

- ✨: Bổ sung thêm mô tả dạng lưới (theo tham số ha.sudungmotabenhly = 1) đối với thực hiện CLS Thăm dò chức năng theo [Mô tả thực hiện cận lâm sàng Thăm dò chức năng `(KHO = 'CN')`](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20th%E1%BB%B1c%20hi%E1%BB%87n%20c%E1%BA%ADn%20l%C3%A2m%20s%C3%A0ng%20Th%C4%83m%20d%C3%B2%20ch%E1%BB%A9c%20n%C4%83ng.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/309
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/459

## [v.3.24.0719.0]()

- ✨: Thực hiện bổ sung form trả kết quả Thăm dò chức năng theo [Mô tả thực hiện cận lâm sàng Thăm dò chức năng `(KHO = 'CN')`](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20th%E1%BB%B1c%20hi%E1%BB%87n%20c%E1%BA%ADn%20l%C3%A2m%20s%C3%A0ng%20Th%C4%83m%20d%C3%B2%20ch%E1%BB%A9c%20n%C4%83ng.md) ![image](https://github.com/dh-hos/Mo-ta-he-thong/assets/112069710/b9668bb2-4d18-4bae-857a-3972caaffd92) và mẫu kết quả tự thiết kế ![image](https://github.com/dh-hos/Mo-ta-he-thong/assets/112069710/58ffae93-96b9-4d08-83d2-bc86e1086f23)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/309
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/459

## [v.3.24.0712.0]()

- 🐛: Sửa lỗi phiếu kết quả điện tim không hiển thị được hình ảnh đã chọn.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/61

## [v.3.24.0711.0]()

- 🐛: Sửa lỗi `Sổ chẩn đoán hình ảnh` mất chức năng lập Ekipt (BV Phụ sản - `92118`).
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/60

## [v.3.24.0704.0]()

- ✨: Thực hiện bổ sung ngày thực hiện y lệnh CĐHA #21.
- ✨: Sửa lỗi - TREO MÁY KHI LƯU KẾT QUẢ SIÊU ÂM #59.
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/21
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/59

## [v.3.24.0626.1]()

- 🐛: Sửa lỗi mẫu tự thiết kế Nội soi TMH không lấy được 6 hình.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/57

## [v.3.24.0626.0]()

- ✨: Thay đổi cách ghi nhận tên tập tin khi chuyển chỉ định. ![image](https://github.com/dh-hos/To_Trien_Khai/assets/112069710/b5f7a066-498a-47dd-9887-1e85738bbb66)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/62

## [v.3.24.0623.0]()

- ✨: Bổ sung chức năng kết xuất chỉ định XQuang sang máy XQuang (BV Tâm Phúc). Theo mô tả [MÔ TẢ KẾT XUẤT DỮ LIỆU CHỈ ĐỊNH SANG MÁY XQUANG](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20k%E1%BA%BFt%20xu%E1%BA%A5t%20d%E1%BB%AF%20li%E1%BB%87u%20ch%E1%BB%89%20%C4%91%E1%BB%8Bnh%20sang%20m%C3%A1y%20XQuang%20-%20BV%20T%C3%A2m%20Ph%C3%BAc%20%5BB%C3%ACnh%20Thu%E1%BA%ADn%5D.md)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/140

## [v.3.24.0613.0]()

- ✨: Bổ sung mẫu tự thiết kế MRI/CT.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/312

## [v.3.24.0606.0]()

- ✨: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68

## [v.3.24.0531.1]()

- ✨: Bổ sung tham số chỉ số huyết áp `huyetap` cho phiếu điện tim tự thiết kế.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/56

## [v.3.24.0531.0]()

- ✨: Bổ sung tham số chỉ số huyết áp `huyetap` cho phiếu điện tim tự thiết kế.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/56

## [v.3.24.0523.0]()

- ✨: Bổ sung các tham số trên mẫu điện tim tự thiết kế, gồm: `ngaykq_ngay, ngaykq_thang, ngaykq_nam, ngaykq_gio, ngaykq_phut, ngaykq_giay` và `diaphuong`.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/56#issuecomment-2122486771

## [v.3.24.0521.2]()

- 🐛: Sửa lỗi thiếu dữ liệu thông tin para cannang và chieucao trên mẫu điện tim tự thiết kế.
- 🐛: Sửa lỗi para Lời dặn/đề nghị mất cỡ chữ trên mẫu điện tim tự thiết kế.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/56

## [v.3.24.0521.1]()

- 🐛: Sửa lỗi thiếu dữ liệu thông tin para cannang và chieucao trên mẫu điện tim tự thiết kế.
- 🐛: Sửa lỗi para Lời dặn/đề nghị mất cỡ chữ trên mẫu điện tim tự thiết kế.
- ☑: Lỗi - BV Phụ Sản Cần Thơ: mẫu kết quả điện tim theo yêu cầu dh-hos/dhg.hospitaldiagnose#56 (comment)

## [v.3.24.0521.0]()

- 🐛: Sửa lỗi không thể hiện được hình trên mẫu điện tim tự thiết kế.
- ☑: https://github.com/dh-hos/dhg.hospitaldiagnose/issues/56