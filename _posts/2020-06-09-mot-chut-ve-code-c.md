---
title: "Một chút về code C"
categories:
  - Blog
tags:
  - code c
---

1. Sự khác nhau giữa i++ và ++i ?  
- i++: Thực thi hàm, biểu thức với i trước, sau đó mới tăng i lên 1 đơn vị.  
- ++i: Tăng i lên 1 đơn vị rồi mới thực thi hàm, biểu thức.

Ví dụ:  
>int i = 0, j = 0;  
printf("%d - %d",i++,++j);  

Kết quả:  
>0 - 1  

Note:
Trong lập trình, ++ hay - - được gọi là toán tử tăng, giảm. Có dạng tiền tố (prefix) đặt trước toán hạng (++i), hậu tố (postfix) đặt sau toán hạng (i++). Nếu đặt riêng i++ và ++i, ý nghĩa được xem như là giống nhau. Có một số ý kiến cho rằng ++i có tốc độ xử lý nhanh hơn i++ vì không tạo thêm biến phụ (phân tích mã Assembly). Thật ra, tùy vào ngôn ngữ và trình biên dịch mà tốc độ xử lý sẽ khác nhau. Xét về cơ bản, ngôn ngữ và trình biên dịch cũng chỉ là do con người viết ra. Nếu đặt riêng i++ và ++i, chung một ý nghĩa, thì tại sao không tối ưu để ra chung một mã Assembly ?  


