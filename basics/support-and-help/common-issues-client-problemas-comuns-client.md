---
description: >-
  Nếu bạn không tìm thấy giải pháp nào bên dưới, vui lòng liên hệ với đội ngũ hỗ
  trợ của chúng tôi trên Discord hoặc WhatsApp.
---

# 🪛 Các vấn đề chung (Khách hàng)

## Arkaik.exe mở lên, nhưng khi nhấn "Chơi", không có gì xảy ra và nó đóng lại

{% embed url="https://youtu.be/alrPDAo3cx0" %}

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

📌 **Hình ảnh:** Quy trình giống như trên!

## **Lỗi: Không thể tìm thấy Tệp với ký tự đặc biệt "????"**

{% embed url="https://youtu.be/7MElYRZ4p8w" %}

**Vấn đề:**

* Khi chạy `Client.exe`, sau khi chọn một nhân vật, trò chơi hiển thị các ký tự đặc biệt dưới dạng `???`, gây ra **sập**.

<figure><img src="../../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

**Nguyên nhân:**

* Gói ngôn ngữ **không chuyển đổi được mã hóa UTF-8** cho các ký tự **Hàn Quốc (Châu Âu phương Tây 1252)**.

**Giải pháp:**\
➡ **Bảng điều khiển** > **Thay đổi định dạng ngày, giờ hoặc số** > **Quản trị (Tab trên cùng)** > **Thay đổi ngôn ngữ hệ thống**

🔹 **Bỏ chọn** ô **UNICODE UTF-8** nếu nó đang được bật, khởi động lại và kiểm tra trò chơi.

<figure><img src="../../.gitbook/assets/image (152).png" alt="" width="329"><figcaption></figcaption></figure>

## **Lỗi trong Client.exe: "Không thể khởi tạo d3d HOẶC tệp grf có vấn đề" hoặc Màn hình trắng**

{% embed url="https://youtu.be/Spq8HxAYCW0" %}

<figure><img src="../../.gitbook/assets/Cannot_init_d3d_or_grf_file_has_problem.png" alt="" width="188"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/800px-Telabranca.png" alt="" width="375"><figcaption><p>Màn hình trắng</p></figcaption></figure>

**Vấn đề:**

* Khi nhấp vào **Client.exe**, không có gì xảy ra, màn hình trắng xuất hiện và trò chơi đóng ngay lập tức, ngay cả sau khi chọn **card đồ họa** trong **RO/OpenSetup.exe**.

**Vấn đề 2:**\* Khi nhấp vào **Chơi** qua **Arkaik.exe** hoặc **Client.exe**, thông báo lỗi **"Không thể khởi tạo d3d HOẶC tệp grf có vấn đề"** xuất hiện (đây là trường hợp phổ biến nhất).

***

#### **Giải pháp cho Vấn đề 2:**

1. Mở **RO/OpenSetup.exe**
2. Chọn **card đồ họa** của bạn
3. Nhấp vào **Áp dụng**

➡ Nếu vấn đề vẫn tiếp diễn, hãy thử **Giải pháp 1** bên dưới.

#### **Nguyên nhân có thể:**

* **Driver card đồ họa** của bạn có thể đã lỗi thời hoặc không được **Ragnarok** nhận diện.
* Một số **laptop RTX 3050** từ **Asus Gaming** gặp phải vấn đề này.

***

#### **Cách kiểm tra vấn đề này:**

1. **Nhấp chuột phải** vào **Client.exe**
2. Chọn **"Khắc phục sự cố tương thích"**
3. Nhấp vào **"Kiểm tra chương trình"**

Nếu trò chơi **chạy nhưng có lỗi** (_như thiếu kết cấu hoặc hình ảnh không chính xác_), hãy tiếp tục với **giải pháp tiếp theo**.

<figure><img src="../../.gitbook/assets/image (153).png" alt="" width="387"><figcaption></figcaption></figure>

\
**Giải pháp bổ sung: "Không thể khởi tạo d3d HOẶC tệp grf có vấn đề"**

\*\*Giải pháp:\*\*1. Mở **Trình quản lý thiết bị** 2. Đi đến **Bộ điều hợp hiển thị** 3. **Vô hiệu hóa** **card đồ họa RTX** của bạn (hoặc GPU chuyên dụng của bạn) 4. Mở lại **Client.exe**

**Giải thích:**

* Nếu trò chơi **mở và hoạt động**, điều đó có nghĩa là **trình kết xuất Vodoo** đang được sử dụng.
* Card đồ họa của bạn có thể **quá hiện đại** và **không hỗ trợ các phiên bản DirectX cũ hơn**.

[<mark style="color:purple;">Link do Video Tutorial</mark>](https://www.youtube.com/watch?v=2dStctdLMeE)

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

## **Lỗi Tải Các Mô-đun Arkaik.exe Trước Màn Hình Đăng Nhập (Ngày & Giờ)**

{% embed url="https://youtu.be/_AesF-DFHbs" %}

**Vấn đề:**

* Khi mở **Arkaik.exe**, trong quá trình tải mô-đun, một **lỗi đỏ** xuất hiện với thông báo:\
  \&#xNAN;**"Máy chủ không thể xác thực yêu cầu"**.

<figure><img src="../../.gitbook/assets/image (155).png" alt="" width="563"><figcaption></figcaption></figure>

**Nguyên nhân:**

* Vấn đề này thường xảy ra trên **Windows 11** vì nó phụ thuộc vào một máy chủ trực tuyến để đồng bộ hóa thời gian hệ thống.

**Giải pháp:**

1. **Đi đến:** \* **Bảng điều khiển** > **Ngày & Giờ** > **Đồng bộ ngay**

<figure><img src="../../.gitbook/assets/image (156).png" alt="" width="332"><figcaption></figcaption></figure>

1. Mở **cài đặt Ngày & Giờ cổ điển** trong Windows.
2. **Điều chỉnh thủ công** ngày và giờ.
3. Đảm bảo giờ hiện tại khớp với phút hiện tại từ **Brasilia (Máy chủ thời gian Google)**.
4. Ngoài ra, hãy bật:
   * **"Thay đổi Múi giờ"**
   * Đồng bộ hóa **"Thời gian Internet"** với máy chủ chính xác.

**Nếu Vấn Đề Vẫn Tiếp Diễn:**

<figure><img src="../../.gitbook/assets/image (157).png" alt=""><figcaption><p><mark style="color:red;"><strong>Nhấp vào Thời gian Internet</strong></mark></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (158).png" alt=""><figcaption><p><mark style="color:red;"><strong>Thay đổi Múi giờ</strong></mark></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

**Lỗi: Không thể lấy URL cập nhật (khi mở arkaik.exe)**\


{% embed url="https://youtu.be/zMdliegZya8" %}

**Vấn đề:** Khi chạy **arkaik.exe**, xuất hiện lỗi cập nhật: **"Không thể lấy URL cập nhật"**, có nghĩa là máy chủ cập nhật đã từ chối kết nối.

**Giải pháp:** Tải xuống **https://1.1.1.1**. Nếu vấn đề vẫn tiếp diễn, **Cloudflare** có thể tối ưu hóa tuyến đường tốt nhất cho internet của bạn.

<figure><img src="../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

## **Màn hình ô vuông màu khi chạy Client.exe**

{% embed url="https://youtu.be/b4LLXuUrKoc" %}

<figure><img src="../../.gitbook/assets/800px-Tela_com_quadrados_coloridos_arkaik_online.png" alt="" width="563"><figcaption></figcaption></figure>

**Vấn đề:**

* Cấu hình này được thiết kế cho **các card đồ họa cũ**. Các **GPU RTX** và **chipset** mới hơn có thể gặp phải vấn đề này.

**Giải pháp:**

1. Đi đến thư mục nơi bạn đã cài đặt trò chơi:
   * **ArkaikOnline/RO/OpenSetup.exe**
   * Hoặc mở **arkaik.exe** > **Cài đặt** > **ROSETUP bên ngoài**2. Tìm một ô kiểm có nhãn **"Bật tăng tốc phần cứng"**, **tắt nó đi**, lưu lại và khởi động lại trò chơi.
2. Nếu vấn đề vẫn tiếp diễn, quay lại cùng một vị trí và:
   * **Thêm một card đồ họa**
   * **Đặt độ phân giải thấp hơn 1366x768**
