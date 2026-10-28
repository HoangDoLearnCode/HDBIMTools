<img width="2052" height="1188" alt="image" src="https://github.com/user-attachments/assets/86d9bcfd-c861-41e0-a755-9771fa26bf0c" /><p align="center">
  <img src="https://raw.githubusercontent.com/HoangDoLearnCode/HDBIMTools/main/assets/LogoHDTool_512px.png" alt="HDBIM Tools Logo" width="120" height="120">
  <h1 align="center">HDBIM Tools</h1>
  <p align="center">
    <b>Bộ công cụ mạnh mẽ hỗ trợ và tối ưu hóa quy trình làm việc tự động trên Autodesk Revit</b>
  </p>
  <p align="center">
    <a href="https://hdbimtools.netlify.app/"><img src="https://img.shields.io/badge/Website-hdbimtools.netlify.app-007acc?style=flat-square&logo=netlify" alt="Website"></a>
    <a href="https://github.com/HoangDoLearnCode/HDBIMTools/releases/latest/download/HDBIM-Setup.exe"><img src="https://img.shields.io/badge/Download-Setup.exe-brightgreen?style=flat-square&logo=github" alt="Download Setup"></a>
    <a href="#"><img src="https://img.shields.io/badge/Revit-2022%20--%202027-0696D7?style=flat-square&logo=autodesk" alt="Revit Versions"></a>
    <a href="#"><img src="https://img.shields.io/badge/.NET-Framework%204.8%20%7C%208.0%20%7C%2010.0-512BD4?style=flat-square&logo=dotnet" alt=".NET"></a>
    <a href="https://youtube.com/@HDBIMTools"><img src="https://img.shields.io/badge/YouTube-@HDBIMTools-FF0000?style=flat-square&logo=youtube" alt="YouTube"></a>
  </p>
</p>

---

## 📌 Giới thiệu

**HDBIM Tools** là bộ Add-in mở rộng toàn diện dành cho Autodesk Revit, được thiết kế chuyên biệt nhằm giúp các Kỹ sư BIM, Kỹ sư Kết cấu và Kiến trúc sư tự động hóa các tác vụ lặp đi lặp lại, tiết kiệm thời gian triển khai mô hình 3D và nâng cao tối đa độ chính xác của hồ sơ bản vẽ kỹ thuật.

> [!IMPORTANT]
> Add-in tương thích hoàn hảo trên các phiên bản **Autodesk Revit từ 2022 đến 2027**, đi kèm giao diện hiện đại hỗ trợ chuyển đổi linh hoạt giữa **Dark Mode** và **Light Mode**.

---

## ✨ Tính năng nổi bật

### ☁️ 1. Thư viện Family Đám mây (Cloud Family Manager)
- **Quản lý tập trung:** Truy cập và quản lý kho lưu trữ file `.rfa` trực tiếp trên đám mây mượt mà.
- **Kéo & thả trực quan (Drag & Drop):** Hỗ trợ xem trước hình ảnh 3D thumbnail và chèn thẳng Family vào dự án ngay trong giao diện Dockable Panel.
- **Đồng bộ thông số tự động:** Tự động trích xuất hình ảnh thu nhỏ và đồng bộ hóa metadata nhanh chóng.

### 🔍 2. Tìm kiếm & Thay thế Tham số (Batch Find & Replace)
- Thao tác tìm kiếm và thay thế chuỗi ký tự hàng loạt cho các tham số (`Parameters`), ký hiệu `Mark`, `Prefix/Suffix` trên toàn bộ mô hình hoặc trên các phần tử được chọn (`Selected Elements`).

### 🏗️ 3. Công cụ Cốt thép & Hình học (Rebar & Geometry Utilities)
- Tự động hóa quá trình bố trí và tạo cốt thép cho các cấu kiện hình học phức tạp, Adaptive Families.
- Công cụ chuyển đổi và tính toán chiều dài cốt thép thông minh, chuẩn xác đến từng milimét.

### 🛠️ 4. Bộ công cụ tiện ích mở rộng (Utilities)
- Tự động hóa quy trình tạo lập và quản lý Sheet, View, Parameter hàng loạt.
- Tích hợp công cụ kết nối AutoCAD LISP và chuẩn hóa cấu trúc dữ liệu đầu vào.

---

## 🖥️ Giao diện ứng dụng & Demo

| Dockable Panel & Cloud Library | Batch Parameter Tools |
| :---: | :---: |
| 🖼️ *(Cập nhật ảnh hoặc GIF demo tại đây)* | 🖼️ *(Cập nhật ảnh hoặc GIF demo tại đây)* |

---

## 🚀 Hướng dẫn Cài đặt

1. Tải bộ cài đặt mới nhất định dạng `.exe` tại mục [Releases](../../releases) hoặc truy cập trực tiếp [Trang chủ HDBIM Tools](https://hdbimtools.netlify.app/).
2. Đóng hoàn toàn các phiên làm việc của Autodesk Revit đang mở trước khi tiến hành cài đặt.
3. Chạy file `HDBIMTools_Setup.exe` và làm theo các bước hướng dẫn trên màn hình.
4. Mở lại Revit, bạn sẽ nhìn thấy Ribbon tab **HDBIM** xuất hiện trên thanh công cụ chính.

---

## 💻 Nền tảng Công nghệ

Dự án được xây dựng dựa trên các tiêu chuẩn phát triển phần mềm hiện đại và tối ưu hiệu suất cho Revit:
- **Ngôn ngữ:** C#
- **Môi trường .NET:** .NET Framework 4.8 / .NET 8.0 / .NET 10.0
- **UI Architecture:** WPF (Windows Presentation Foundation) kết hợp Material Design
- **Core SDK:** `Nice3point.Revit.Sdk`

---

## 📬 Liên hệ & Hỗ trợ

Mọi đóng góp, báo lỗi hoặc yêu cầu phát triển tính năng mới, xin vui lòng liên hệ qua các kênh chính thức sau:

- **Tác giả:** HOÀNG ĐỖ (BIM Engineer)
- **📧 Email:** [vanhoang211295@gmail.com](mailto:vanhoang211295@gmail.com)
- **📞 Zalo / Hotline:** 034 333 5095
- **🌐 Website:** [hdbimtools.netlify.app](https://hdbimtools.netlify.app/)
- **📺 YouTube Channel:** [@HDBIMTools](https://youtube.com/@HDBIMTools)
- **🐙 GitHub Profile:** [HoangDoLearnCode](https://github.com/HoangDoLearnCode)

---

<p align="center">
  <i>Copyright © 2026 HOÀNG ĐỖ. Designed for BIM Efficiency.</i>
</p>
