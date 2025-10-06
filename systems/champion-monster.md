---
description: >-
  Quái vật Champion là một quái vật được máy chủ triệu hồi một cách động sau khi
  một số điều kiện nhất định được đáp ứng.
---

# 🏆 Quái Vật Vô Địch

<figure><img src="../.gitbook/assets/mmmm.gif" alt=""><figcaption><p><mark style="color:red;"><strong>Quái Vật Champion Đang Hành Động</strong></mark></p></figcaption></figure>

## **Đặc Điểm**

* Khi một **Champion** xuất hiện, nó sẽ được thông báo đến tất cả người chơi trên bản đồ.
* **Champions mang lại 30 lần kinh nghiệm hơn và có tỷ lệ rơi đồ gấp 10 lần.**
* Giờ đây, vật phẩm Đồng Tiền Hoàng Gia có thể rơi ra từ bất kỳ quái vật vô địch nào.
* Tỷ lệ rơi bắt đầu từ 0,1% từ quái vật vô địch cấp 1, cho đến 5% từ quái vật vô địch cấp 99 trở lên.

***

## **Công Thức Triệu Hồi**

Phép tính được áp dụng khi tiêu diệt một quái vật để xác định xem một Champion có được triệu hồi hay không như sau:

```
mathematicaCopiarEditarSummon Chance += [(Monster Level / 100) * Number of Players on the Map]%
```

### **Ví Dụ:**

\
Nếu bạn đang trong một nhóm với 5 người bạn trên bản đồ và tiêu diệt một quái vật cấp 25 **25 lần**, thì:

Cơ hội để quái vật này trở thành một Champion là **1.25%**.

Nếu việc triệu hồi không xảy ra, cơ hội tiếp theo sẽ tăng lên **2.50%**, và cứ như vậy.

***

## **Các Loại Champion**

* Loại Champion được triệu hồi là ngẫu nhiên. Bảng dưới đây hiển thị các đặc điểm của từng quái vật.

| Loại    | Sát thương | Máu   | Di chuyển      | Kháng        | Đặc điểm                     |
| ------- | ---------- | ----- | -------------- | ------------ | ---------------------------- |
| Ventus  | +700%      | +900% | 30             | Gió = 90%    | Nome                         |
| Solid   | +700%      | +900% | 700            | Đất = 90%    | 1% cơ hội phá vũ khí         |
| Necro   | +700%      | +900% | 1500           | Undead = 90% | Hồi phục 3% HP của quái      |
| Fairer  | +700%      | +900% | Không thể ngắt | Lửa = 90%    | Luôn có \[Endure]            |
| Elusive | +700%      | +900% | Không thể ngắt | Nome         | Miễn nhiễm sát thương vật lý |

\## \*\*Thông số hệ thống\*\*

<table><thead><tr><th width="169">Thông số</th><th>Loại</th></tr></thead><tbody><tr><td>Liên kết</td><td>Không có</td></tr><tr><td>Hạn chế</td><td>Không hoạt động với <strong>quái vật huyền thoại</strong>, và chỉ một <strong>Quái vật Champion</strong> được triệu hồi tại một thời điểm trong khi một quái vật khác vẫn còn sống trên cùng một bản đồ.</td></tr></tbody></table>
