Code được coi là sạch nếu mọi người trong team có thể dễ dàng đọc hiểu nó. 
Clean code đơn giản là: Dễ đọc, dễ thay đổi, dễ mở rộng và dễ bảo trì.

![1520178736603](https://git.miagi-so.net/uploads/-/system/personal_snippet/22/dd64f8d3cef22b3f4e6c0805fdc206c0/1520178736603.jpeg)

## Các nguyên tắc chung
### Tuân theo các quy ước tiêu chuẩn 
Mỗi nhóm khi làm việc phải tuân theo các quy ước tiêu chuẩn chung (cho mọi ngành nghề).  
Các tiêu chuẩn coding sẽ quy định các nội dung như: cách khai báo biến; cách đặt tên lớp, phương thức và biến; đặt dấu mở ngoặc ở đâu,...

Tài liệu coding conventions là không cần thiết, chúng sẽ được thể hiện ở trong code.  
Tất cả thành viên trong nhóm đều cần tuân thủ các quy tắc.

Một số công cụ check coding conventions:
- Ruby: rubocop
- PHP: phpcs
- JS: ESlint

![06f0b6de-6490-4f45-b91e-601c2a04da67](https://git.miagi-so.net/uploads/-/system/personal_snippet/22/1ec20df220b87520b46d06233bc8b343/06f0b6de-6490-4f45-b91e-601c2a04da67.jpeg)

https://git.miagi-so.net/vinhvd/guidelines

### Giữ cho mọi thứ đơn giản: Đơn giản hơn thì tốt hơn
`KISS: Keep It Simple Stupid`. 

![1_WZmVF9vJAyn8tO1g3lVa9w-676x450](https://git.miagi-so.net/uploads/-/system/personal_snippet/22/beafa07fd1e802c3bc0d636bb337a796/1_WZmVF9vJAyn8tO1g3lVa9w-676x450.png)

Giảm bớt sự phức tạp đến mức tối đa có thể.  
Luôn đặt ra câu hỏi: Có cách nào khác đơn giản hơn để thực hiện việc này không?  

`DRY: Don't Repeat Yourself`. 

`YAGNI: You Aren't Gonna Need It`. 

Always implement things when you actually need them, never when you just foresee that you need them. 

*Cho thấy bạn thực sự thông minh bằng cách nói cho mọi người biết những gì họ cần làm một cách nhanh chóng và đơn giản – những người cố gắng phóng đại kiến ​​thức, kỹ năng của mình có thể mất rất nhiều thời gian. Khối lượng những gì bạn nói, viết hay làm ít quan trọng hơn giá trị bạn truyền đạt.*

Design Principles vs Design Patterns

### Quy tắc hướng đạo sinh: Luôn rời đi với khu cắm trại sạch hơn lúc bạn tìm thấy nó.

Boy Scout Rule được phát biểu dưới nhiều dạng khác nhau như:
- always leave the code you're editing a little better than you found it
- always leave the code cleaner/better than you found it
- Always check a module in cleaner than when you checked it out

![93cab7fc-950a-4ea9-88ed-e504b4d43a95.webp](https://git.miagi-so.net/uploads/-/system/personal_snippet/22/d1423c2f7a3cab4206fb1e592e42257d/93cab7fc-950a-4ea9-88ed-e504b4d43a95.webp)

### Luôn tìm nguồn gốc của vấn đề

- Tập trung vào lỗi của hệ thống, không phải lỗi của cá nhân
- Đi từ những nguyên nhân chuyên biệt về chuyên môn đến các nguyên nhân thông thường về quản lý
- Đặt câu hỏi tại sao nhiều lân (5 Whys)
- Phân tích và xác định những thay đổi trong qui trình có thể giúp giảm nguy cơ hoặc ngăn chặn sự cố tiếp tục xảy ra
