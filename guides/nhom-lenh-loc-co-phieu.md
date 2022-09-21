---
description: Nhóm lệnh dùng để lọc tìm các cổ phiếu thỏa tiêu chí của bộ lọc
---

# 🌟 Nhóm lệnh lọc cổ phiếu

<mark style="color:blue;">**/filtervolume**</mark>** :** Lọc các cổ phiếu thỏa các tiêu chí sau:

1. 3% <= <mark style="color:purple;">**% thay đổi giá**</mark> <= 6%&#x20;
2. Khối lượng giao dịch của cổ phiếu ngày hiện tại >= 1,000,000 và giá trị vốn hóa >=1000 tỷ đồng
3. Khối lượng giao dịch ngày hiện tại >= Khối lượng giao dịch trung bình 20 ngày

<mark style="color:blue;">**/filterVol MA Hệ số**</mark>

**Ví dụ**: <mark style="color:blue;">**/filterVol 20 1.5**</mark> : Lọc cổ phiếu có Khối lượng giao dịch ngày hiện tại >= Khối lượng giao dịch trung bình 20 ngày <mark style="color:red;">**x 1.5**</mark>

{% hint style="danger" %}
<mark style="color:red;">**20 và 1.5 là biến số người dùng có thể tùy chỉnh các thông số này.**</mark>

Ví dụ: <mark style="color:blue;">**/filterVol 10 0.5**</mark>
{% endhint %}

{% hint style="success" %}
Thông số chung cho bộ lọc MACD: ema=26, signal ema=9
{% endhint %}

<mark style="color:blue;">**/MACDUp:**</mark> Lọc các cổ phiếu có đường MACD cắt lên trên đường Signal

<mark style="color:blue;">**​/MACDDown:**</mark> Lọc các cổ phiếu có đường MACD cắt xuống dưới đường Signal

<mark style="color:blue;">**/MACDUpZero:**</mark> Lọc các cổ phiếu có đường MACD cắt lên trên đường Zero

<mark style="color:blue;">**/MACDDownZero:**</mark> Lọc các cổ phiếu có đường MACD cắt xuống dưới đường Zero

<mark style="color:blue;">**/Canslima8**</mark>: Lọc các cổ phiếu có biên lợi nhuận quý và năm >=25% và duy trì liên tục trên 3 kỳ báo cáo tài chính
