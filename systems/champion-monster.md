---
description: >-
  Quái vật Champion là một quái vật được máy chủ triệu hồi một cách động sau khi
  một số điều kiện nhất định được đáp ứng.
---

# 🏆 Quái Vật Champion

<figure><img src="../.gitbook/assets/mmmm.gif" alt=""><figcaption><p><mark style="color:red;"><strong>Quái Vật Champion Đang Hành Động</strong></mark></p></figcaption></figure>

## **Đặc Điểm**

* Khi một **Champion** xuất hiện, nó sẽ được thông báo đến tất cả người chơi trên bản đồ.
* **Champions mang lại 30 lần kinh nghiệm hơn và có tỷ lệ rơi đồ gấp 10 lần.**

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

## **Các Loại Champion*** Loại Champion được triệu hồi là ngẫu nhiên. Bảng dưới đây hiển thị các đặc điểm của từng quái vật.

<table><thead><tr><th width="102">Loại</th><th width="92">Sát thương</th><th width="151">Sức khỏe</th><th width="147">Kháng</th><th>Tính năng</th></tr></thead><tbody><tr><td><mark style="background-color:green;">Ventus</mark></td><td>+7%</td><td>30</td><td>Gió = 90%</td><td>Nome</td></tr><tr><td><mark style="background-color:yellow;">Solid</mark></td><td>+7%</td><td>700</td><td>Đất = 90%</td><td>Có 1% cơ hội làm gãy vũ khí</td></tr><tr><td><mark style="background-color:purple;">Necro</mark></td><td>+7%</td><td>1500</td><td>Undead = 90%</td><td>Khôi phục 3% HP của mob</td></tr><tr><td><mark style="background-color:orange;">Fairer</mark></td><td>+7%</td><td>Không bị gián đoạn</td><td>Fire = 90%</td><td>Có [Endure] đang hoạt động</td></tr><tr><td><mark style="background-color:blue;">Elusive</mark></td><td>+7%</td><td>Không bị gián đoạn</td><td>Nome</td><td>Không nhận sát thương vật lý</td></tr></tbody></table>## **Thông số hệ thống**

<table><thead><tr><th width="169">Thông số</th><th>Loại</th></tr></thead><tbody><tr><td>Liên kết</td><td>Không có</td></tr><tr><td>Hạn chế</td><td>Không hoạt động với <strong>quái vật huyền thoại</strong>, và chỉ một <strong>Quái vật Champion</strong> được triệu hồi tại một thời điểm trong khi một quái vật khác vẫn còn sống trên cùng một bản đồ.</td></tr></tbody></table>