---
title: How I Built This Blog
tags:
  - tech
  - blog
  - tutorial
plantedAt: 2024-03-03
---
> [!quote] Socrates
> Every action has its pleasures and its price.
## Lý do mình viết blog?
- Cũng có nhiều nguyên nhân lắm, đầu tiên chắc là do tính cách mình khá hướng nội nên khi giao tiếp với người khác sẽ hơi tốn năng lượng dẫn đến mình thành người ngại giao tiếp luôn. Điều này làm bản thân mình và bạn bè nhiều lúc sẽ không cập nhật được tình hình của nhau, nên viết blog này để mọi người hiểu con người mình hơn, rồi khi gặp nhau sẽ dễ nói chuyện hơn.
- Thư hai là mình cũng muốn tạo Second Brain như một nơi lưu trữ những thông tin, tri thức mà mình thu nhặt được, phần nhiều là những điều có ích và mình sử dụng thường xuyên, nên hy vọng nó biết đâu vào một ngày đẹp trời nó cũng giúp ích cho bạn thì sao.
- Ngoài ra, để tránh góc nhìn một chiều và bị bias những thông tin sai lệch, thì mình cũng muốn một nơi mà được các bạn có thể cùng đọc và góp ý mang tính chất xây dựng để nội dung trở nên tốt hơn.
## Blog của mình có gì?
Free, Fast, Full-text Search and Feature List
### Free
- Đúng vậy, để tạo một blog như này bạn không mất gì cả từ server host đến domain bằng cách là mình sẽ dựng dựa trên Github Page
### Fast
- Thời gian built cũng cực kỳ nhanh do blog kế thừa từ một project open-source có tên là Quartz. Hiểu nôm na là các bạn ấy đã lo cho hết cả khu vườn từ a-z rồi, việc của mình chỉ là trồng cây thôi.
- Thời gian viết content (trồng cây) cũng rất nhanh do sử dụng định dạng Markdown nên chỉ cần bạn tìm hiểu đôi chút về syntax thì có thể tạo được một blog đầy đủ tính năng mà còn đẹp nữa.
### Full-text Search
> [!info] Theo như tác giả ghi thì:
> Full-text search in Quartz is powered by [Flexsearch](https://github.com/nextapps-de/flexsearch). It’s fast enough to return search results in under 10ms for Quartzs as large as half a million words.
- Các bạn có thể click vào ô `Search` hoặc nhấn `Ctr+K` và nhập một từ khoá nào đấy để xem nó nhanh như thế nào.
- Việc search trên toàn bộ blog này giúp chúng ta có thể xem trước blog qua đó tìm được đúng nội dung  mà mình muốn. Cá nhân mình thấy nó tiết kiệm được rất nhiều thời gian và công sức luôn.
- Thêm một ý là nếu bạn đọc blog trên desktop thì bên tay phải sẽ có Graph View. Tính năng này giúp hiển thị một cách trực quan các page khác liên quan đến nội dung mình đang đọc. Bạn có thể click vào các chấm trong đó để chuyển qua page mình muốn đọc.
### Feature list
Lý do mình chọn Quartz là do open-source này hỗ trợ rất nhiều tính năng support cho việc đọc, ôn tập.
Ví dụ như:
- Bạn có thể tạo một callout như thế này:
> [!question]+ Can callouts be nested?
>
> > [!todo]- Yes!, they can.
> >
> > > [!example] You can even use multiple layers of nesting.
Hay
- Di chuyển con chuột vô từ khoá để xem nội dung chi tiết link ở page định nghĩa nó:
	- như này: [about me](index)

Và nhiều thứ khác nữa, có thể đọc thêm tại [đây](https://quartz.jzhao.xyz/features/)
## Đi tìm garden mình thích nhất
Ban đầu thì mình xây dựng blog dựa trên một open-source khác tên là [JustTheDoc](https://just-the-docs.com/) cũng support đầy đủ tính năng như Quartz. Tuy nhiên syntax markup trên Markdown hơi khác một chút so với Obsidian làm cho mỗi khi mình muốn publish một note nào đó lên blog thì sẽ phải sửa lại một chút. Việc này gây vừa tốn thời gian edit lại vừa tốn không gian do mình sẽ phải lưu 2 bản mà nội dung không khác nhau mấy. Cho đến khi mình tìm thấy Quartz thì giải quyết được vấn đề này, hơn nữa còn support thêm Graph View nên quá tiện luôn.
## Bắt tay vào làm thôi
Okay, nếu đọc tới đây và thấy thích thú thì sao bạn không thử tự xây dựng cho mình một blog ?
Để tiện thì mình sẽ tạo ra 2 bài chia sẻ luôn:
- Nếu bạn biết là không muốn động tới code thì có thể đọc bài [này](tech/tutorial/tech_02_handson_built_blog_for_novice)
- Bạn muốn tìm hiểu sâu hơn thì nên xem bài [này](tech/tutorial/tech_03_handson_built_blog_for_nerd)
## Your turn

 > [!todo]- Yes, you can!
 > Hãy viết lên câu chuyện của riêng bạn

> [!info]
> Nếu thấy hay hãy để lại 1 star cho mình tại [Github](https://github.com/hoanshiro/garden) or ủng hộ mình ly cà phê nhá.

---
[!["Buy Me A Coffee"](images/bmc-logo.svg)](https://www.buymeacoffee.com/hoanshirof)
