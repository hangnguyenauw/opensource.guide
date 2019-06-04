---
lang: Tiếng Việt
title: Bắt đầu một dự án nguồn mở
description: Tìm hiểu về nguồn mở và sẵn sàng chạy dự án riêng của bạn.
class: Người mới bắt đầu
toc:
  the-what-and-why-of-open-source: "Nguồn mở là gì và tại sao dùng nguồn mở?"
  should-i-launch-my-own-open-source-project: "Tôi có nên khởi chạy dự án nguồn mở của riêng mình không?"
  launching-your-own-open-source-project: "Launching your own open source project"
  naming-and-branding-your-project: "Đặt tên và xây dựng thương hiệu cho dự án của bạn"
  your-pre-launch-checklist: "Checklist của bạn trước khi khởi chạy dự án"
order: 2
image: /assets/images/cards/beginner.png
related:
  - finding
  - building
---

## Nguồn mở là gì và tại sao dùng nguồn mở?

Vì vậy, bạn đang suy nghĩ về việc bắt đầu với nguồn mở? Xin chúc mừng! Thế giới đánh giá cao sự đóng góp của bạn. Hãy nói về nguồn mở là gì và tại sao mọi người làm điều đó.

### "Nguồn mở" nghĩa là gì?

Khi một dự án là nguồn mở, điều đó có nghĩa là **bất kỳ ai cũng có thể xem, sử dụng, sửa đổi và phân phối dự án của bạn cho bất kỳ mục đích nào**. Các quyền này được thi hành thông qua [giấy phép nguồn mở](https://opensource.org/licenses).

Nguồn mở rất mạnh vì nó làm giảm các rào cản đối với việc áp dụng, cho phép các ý tưởng lan truyền nhanh chóng.

Để hiểu cách thức hoạt động của nó, hãy tưởng tượng bạn của bạn đang có một bữa tiệc  potluck, và bạn mang theo một chiếc bánh anh đào.

* Tất cả mọi người đều thử cái bánh (_sử dụng_)
* Cái bánh rất tuyệt! Mọi người hỏi về bạn nguyên liệu làm bánh (_xem_)
* Một người bạn, tên Alex, một đầu bếp chuyên về bánh ngọt, đề nghị giảm đường (_chỉnh sửa_)
* Một người bạn khác, Lisa, yêu cầu sử dụng nó cho bữa tối vào tuần tới (_phân phối_)

Để so sánh, một quy trình nguồn đóng sẽ là bạn đi đến một nhà hàng và gọi một lát bánh anh đào. Bạn phải trả một khoản phí để ăn chiếc bánh và nhà hàng có thể sẽ không cung cấp công thức của họ cho bạn. Nếu bạn sao chép chính xác chiếc bánh của họ và bán nó dưới tên của chính bạn, nhà hàng có thể có hành động chống lại bạn.

### Tại sao lại có nguồn mở

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/kentcdodds?s=180" class="pquote-avatar" alt="avatar">
  Một trong những trải nghiệm bổ ích nhất mà tôi có được khi sử dụng và cộng tác trên nguồn mở đến từ các mối quan hệ mà tôi xây dựng với các nhà phát triển khác đã gặp phải nhiều vấn đề tương tự tôi gặp phải.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["How getting into Open Source has been awesome for me"](https://kentcdodds.com/blog/how-getting-into-open-source-has-been-awesome-for-me)
  </p>
</aside>

[Có rất nhiều lý do](https://ben.balter.com/2015/11/23/why-open-source/) tại sao một cá nhân hoặc tổ chức sủ dụng nguồn mở. Một số ví dụ có thể bao gồm:

* **Sự hợp tác:** Các dự án nguồn mở có thể được thay đổi bởi bất cứ ai. [Exercism](https://github.com/exercism/), ví dụ, là một nền tảng bài tập lập trình với hơn 350 người đóng góp.

* **Tiếp nhận và phối lại:** Các dự án nguồn mở có thể được sử dụng bởi bất kỳ ai cho gần như mọi mục đích. Mọi người thậm chí có thể sử dụng nó để xây dựng những thứ khác. [WordPress](https://github.com/WordPress), ví dụ, được bắt đầu như là một nhánh của dự án có sẵn tên là [b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md).

* **Minh bạch:** Bất cứ ai cũng có thể kiểm tra một dự án nguồn mở để tìm lỗi hoặc sự không nhất quán. Vấn đề minh bạch cho các chính phủ như [Bulgaria](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) or the [United States](https://sourcecode.cio.gov/), các ngành được quy định như ngân hàng hoặc chăm sóc sức khỏe và phần mềm bảo mật như [Let's Encrypt](https://github.com/letsencrypt).

Nguồn mở cũng không chỉ dành cho phần mềm. Bạn có thể mở mọi thứ từ bộ dữ liệu đến sách. Hãy xem [GitHub Explore](https://github.com/explore) để biết ý tưởng về những gì khác bạn có thể sử dụng nguồn mở.

### Nguồn mở có "miễn phí" không?

Một trong những điểm hấp dẫn nhất của nguồn mở là nó không tốn tiền. "Miễn phí", tuy nhiên, là sản phẩm phụ của giá trị tổng thể của nguồn mở.

Bởi vì [giấy phép nguồn mở yêu cầu] (https://opensource.org/osd-annotated) mà bất kỳ ai cũng có thể sử dụng, sửa đổi và chia sẻ dự án của bạn cho gần như mọi mục đích, bản thân các dự án có xu hướng miễn phí. Nếu dự án tốn tiền để sử dụng, bất kỳ ai cũng có thể tạo một bản sao hợp pháp và sử dụng phiên bản thay thế miễn phí.

Kết quả là, hầu hết các dự án nguồn mở đều miễn phí, nhưng "miễn phí" không phải là một phần của định nghĩa nguồn mở. Có nhiều cách để tính phí cho các dự án nguồn mở gián tiếp thông qua cấp phép kép hoặc các tính năng hạn chế, trong khi vẫn tuân thủ định nghĩa chính thức về nguồn mở.

## Tôi có nên khởi chạy dự án nguồn mở của riêng mình không?

Câu trả lời ngắn gọn là có, bởi vì dù kết quả thế nào, khởi chạy dự án của riêng bạn là một cách tuyệt vời để tìm hiểu cách thức nguồn mở hoạt động.

Nếu bạn chưa bao giờ mở nguồn dự án trước đây, bạn có thể lo lắng về những gì mọi người sẽ nói, hoặc liệu có ai sẽ chú ý gì không. Nếu điều này nghe có vẻ giống bạn, bạn không đơn độc!

Công việc nguồn mở cũng giống như bất kỳ hoạt động sáng tạo nào khác, cho dù đó là viết hay vẽ. Bạn có thể cảm thấy đáng sợ khi chia sẻ công việc của mình với mọi người, nhưng cách duy nhất để trở nên tốt hơn là luyện tập - ngay cả khi bạn không có khán giả.

Nếu bạn chưa bị thuyết phục, hãy dành một chút thời gian để suy nghĩ về mục tiêu của bạn.

### Đặt mục tiêu của bạn

Mục tiêu có thể giúp bạn tìm ra những việc cần làm, những gì nên nói không với và nơi bạn cần sự giúp đỡ từ người khác. Bắt đầu bằng cách tự hỏi, _tại sao tôi lại mở nguồn cho dự án này? _

Không có câu trả lời chính xác cho câu hỏi này. Bạn có thể có nhiều mục tiêu cho một dự án hoặc các dự án khác nhau với các mục tiêu khác nhau.

Nếu mục tiêu duy nhất của bạn là thể hiện công việc của mình, bạn thậm chí có thể không muốn đóng góp, và thậm chí nói như vậy trong file README của bạn. Mặt khác, nếu bạn muốn những người đóng góp, bạn sẽ đầu tư thời gian vào tài liệu rõ ràng và khiến người mới cảm thấy được chào đón.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mavris?s=180" class="pquote-avatar" alt="avatar">
  Tại một số điểm, tôi đã tạo một tùy chỉnh UIAlertView mà tôi đang sử dụng ... và tôi quyết định biến nó thành nguồn mở. Vì vậy, tôi đã sửa đổi nó để năng động hơn và tải nó lên GitHub. Tôi cũng đã viết tài liệu đầu tiên của mình giải thích cho các nhà phát triển khác cách sử dụng nó trong các dự án của họ. Có lẽ không ai từng sử dụng nó vì đây là một dự án đơn giản nhưng tôi cảm thấy tốt về sự đóng góp của mình.
  <p markdown="1" class="pquote-credit">
— @mavris, ["Các nhà Phát triển phần mềm tự học: Tại sao Nguồn mở lại quan trọng đối với chúng tôi"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576)
  </p>
</aside>

Khi dự án của bạn phát triển, cộng đồng của bạn có thể cần nhiều hơn là những dòng code từ bạn. Trả lời các vấn đề, xem lại các dòng lệnh và truyền giáo cho dự án của bạn là tất cả các nhiệm vụ quan trọng trong một dự án nguồn mở.

Mặc dù lượng thời gian bạn dành cho các nhiệm vụ không mã hóa sẽ phụ thuộc vào quy mô và phạm vi dự án của bạn, bạn nên chuẩn bị như một người bảo trì để tự giải quyết chúng hoặc tìm ai đó giúp bạn.

** Nếu bạn là một phần của công ty mở nguồn cho một dự án, ** hãy chắc chắn rằng dự án của bạn có các nguồn lực nội bộ mà nó cần để phát triển. Bạn sẽ muốn xác định ai chịu trách nhiệm duy trì dự án sau khi khởi chạy và cách bạn chia sẻ những nhiệm vụ đó với cộng đồng của mình.

Nếu bạn cần một ngân sách dành riêng hoặc nhân sự cho việc quảng bá, vận hành và duy trì dự án, hãy bắt đầu những cuộc trò chuyện đó sớm.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/captainsafia?s=180" class="pquote-avatar" alt="avatar">
  Khi bạn bắt đầu chuyển dự án của bạn thành nguồn mở, điều quan trọng là đảm bảo rằng các quy trình quản lý của bạn xem xét các đóng góp và khả năng của cộng đồng xung quanh dự án của bạn. Đừng ngại liên quan đến những người đóng góp không được tuyển dụng trong doanh nghiệp của bạn trong các khía cạnh chính của dự án - đặc biệt nếu họ là những người đóng góp thường xuyên.
  <p markdown="1" class="pquote-credit">
— @captainsafia, ["Vì vậy, bạn muốn mở nguồn một dự án, eh?"](https://dev.to/captainsafia/so-you-wanna-open-source-a-project-eh-5779)
  </p>
</aside>

### Đóng góp cho các dự án khác

Nếu mục tiêu của bạn là học cách cộng tác với người khác hoặc hiểu cách hoạt động của nguồn mở, hãy xem xét việc đóng góp cho một dự án hiện có. Bắt đầu với một dự án mà bạn đã sử dụng và yêu thích. Đóng góp cho một dự án có thể đơn giản như sửa lỗi chính tả hoặc cập nhật tài liệu.

Nếu bạn không chắc chắn làm thế nào để bắt đầu như một người đóng góp, hãy xem [Hướng dẫn cách đóng góp cho nguồn mở] của chúng tôi (../how-to-contribute/).

## Khởi chạy dự án nguồn mở của riêng bạn

Không có thời gian hoàn hảo để mở nguồn công việc của bạn. Bạn có thể mở nguồn một ý tưởng, một công việc đang tiến hành hoặc sau nhiều năm là nguồn đóng.

Nói chung, bạn nên mở nguồn dự án của bạn khi bạn cảm thấy thoải mái về việc có người khác xem và đưa ra phản hồi về công việc của bạn.

Bất kể giai đoạn nào bạn quyết định mở nguồn dự án của mình, mọi dự án nên bao gồm các tài liệu sau:

* [Giấy phép nguồn mở](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [Hướng dẫn đóng góp](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [Quy tắc ứng xử](../code-of-conduct/)

Là người bảo trì, các thành phần này sẽ giúp bạn truyền đạt kỳ vọng, quản lý đóng góp và bảo vệ các quyền hợp pháp của mọi người (bao gồm cả quyền của bạn). Chúng làm tăng đáng kể cơ hội của bạn để có một trải nghiệm tích cực.

Nếu dự án của bạn nằm trên GitHub, việc đặt các tệp này vào thư mục gốc của bạn với tên tệp được đề xuất sẽ giúp GitHub nhận ra và tự động hiển thị chúng cho độc giả của bạn.

### Chọn giấy phép

Giấy phép nguồn mở đảm bảo rằng những người khác có thể sử dụng, sao chép, sửa đổi và đóng góp lại cho dự án của bạn mà không phải chịu hậu quả. Nó cũng bảo vệ bạn khỏi các tình huống pháp lý có liên quan. **Bạn phải bao gồm giấy phép khi bạn khởi chạy một dự án nguồn mở.**

Công việc pháp lý rất nghiêm túc. Tin tốt là bạn có thể sao chép và dán giấy phép hiện có vào kho lưu trữ của mình. Nó sẽ chỉ mất một phút để bảo vệ cho sự cố gắng của bạn.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) là các giấy phép nguồn mở phổ biến nhất, nhưng [cũng có nhiều lựa chọn khác](https://choosealicense.com) để chọn.

Khi bạn tạo một dự án mới trên GitHub, bạn được cung cấp tùy chọn để chọn giấy phép. Việc bao gồm một giấy phép nguồn mở sẽ làm cho dự án GitHub của bạn trở thành nguồn mở.

![Chọn một giấy phép](/assets/images/starting-a-project/repository-license-picker.png)

Nếu bạn có câu hỏi hoặc thắc mắc khác xung quanh các khía cạnh pháp lý của việc quản lý dự án nguồn mở, [chúng tôi sẽ trả lời cho bạn](../legal/).

### Viết README file

READMEs làm nhiều hơn việc giải thích cách sử dụng dự án của bạn. Họ cũng giải thích lý do tại sao dự án của bạn quan trọng và những gì người dùng của bạn có thể làm với nó.

Trong file README, hãy cố gắng trả lời các câu hỏi sau:

* Dự án này là gì?
* Tại sao dự án này hữu ích?
* Làm thế nào để tôi bắt đầu?
* Tôi có thể nhận thêm trợ giúp ở đâu nếu tôi cần?

Bạn có thể sử dụng file README của mình để trả lời các câu hỏi khác, như cách bạn xử lý các đóng góp, mục tiêu của dự án là gì và thông tin về giấy phép và phân bổ. Nếu bạn không muốn chấp nhận đóng góp, hoặc dự án của bạn chưa sẵn sàng để sử dụng, hãy viết thông tin này xuống.
<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/tracymakes?s=180" class="pquote-avatar" alt="avatar">
  Tài liệu tốt hơn có nghĩa là nhiều người dùng hơn, ít yêu cầu hỗ trợ hơn và nhiều người đóng góp hơn. (...) Hãy nhớ rằng độc giả của bạn không phải là bạn. Có những người có thể đến với một dự án có những trải nghiệm hoàn toàn khác nhau.
  <p markdown="1" class="pquote-credit">
— @tracymakes, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

Đôi khi, mọi người tránh viết file README vì họ cảm thấy dự án chưa hoàn thành hoặc họ không muốn đóng góp. Đây là tất cả những lý do rất tốt để viết một file README.

Để có thêm cảm hứng, hãy thử sử dụng @dguo's ["Hướng dẫn viết file README](https://www.makeareadme.com/) hoặc @PurpleBooth's [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) để viết một file README hoàn chỉnh.

Khi bạn bao gồm tệp README trong thư mục gốc, GitHub sẽ tự động hiển thị nó trên trang chủ của kho lưu trữ.

### Viết hướng dẫn để đóng góp vào dự án của bạn

File HƯỚNG DẪN sẽ cho người khác biết cách để tham gia vào dự án của bạn. Ví dụ, bạn có thể kèm thêm thông tin về:

* Cách gửi báo cáo về một lỗi nào đó (thử dùng [mẫu về lỗi và thêm yêu cầu](https://github.com/blog/2111-issue-and-pull-request-templates))
* Cách đề xuất một tính năng mới
* Cách thiết lập môi trường của bạn và chạy thử nghiệm

Ngoài các chi tiết kỹ thuật, file HƯỚNG DẪN còn là cơ hội để truyền đạt những kỳ vọng của bạn về những đóng góp, như là:

* Các loại đóng góp bạn đang tìm kiếm
* Lộ trình hoặc tầm nhìn của bạn cho dự án
* Làm thế nào những người đóng góp nên (hoặc không nên) liên lạc với bạn

Sử dụng một, giai điệu thân thiện ấm áp và cung cấp gợi ý cụ thể cho những đóng góp (như viết tài liệu, hoặc làm một trang web) có thể làm cho những người mới cảm thấy chào đón và háo hức tham gia.

Ví dụ, [Quản trị viên](https://github.com/activeadmin/activeadmin/) bắt đầu [file hướng dẫn](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) với:

> Trước hết, cảm ơn bạn đã xem xét đóng góp cho Active Admin. Chính những người như bạn đã khiến Active Admin trở thành một công cụ tuyệt vời.

Trong giai đoạn đầu tiên của dự án, file HƯỚNG DẪN của bạn có thể đơn giản. Bạn phải luôn giải thích cách báo cáo lỗi hoặc báo cáo sự cố và bất kỳ yêu cầu kỹ thuật nào (như kiểm tra) để đóng góp.

Theo thời gian, bạn có thể thêm các câu hỏi thường gặp khác vào file HƯỚNG DẪN của mình. Viết ra thông tin này có nghĩa là ít người sẽ hỏi bạn những câu hỏi lặp đi lặp lại tương tự.

Để được trợ giúp thêm với việc file HƯỚNG DẪN, hãy xem @nayafia's [mẫu hướng dẫn đóng góp](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) hoặc @mozilla's ["Cách viết CONTRIBUTING.md"](https://mozillascience.github.io/working-open-workshop/contributing/).

Liên kết file HƯỚNG DẪN từ file README của bạn, để nhiều người thấy nó hơn. Nếu bạn [đặt file HƯỚNG DẪN trong kho lưu trữ của dự án](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub sẽ tự động liên kết đến tệp của bạn khi cộng tác viên báo cáo lỗi hoặ thêm mới yêu cầu.

![Hướng dẫn đóng góp](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### Thiết lập bộ quy tắc ứng xử

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mlynch?s=180" class="pquote-avatar" alt="avatar">
  Tất cả chúng tôi đều có những trải nghiệm khi chúng tôi phải đối mặt với những gì có lẽ là lạm dụng khi một người bảo trì cố gắng giải thích lý do tại sao một thứ gì đó phải là một cách nhất định, hoặc là một người dùng ... hỏi một câu hỏi đơn giản. (...) Một bộ quy tắc ứng xử trở thành một tài liệu dễ tham khảo và có thể liên kết cho thấy nhóm của bạn rất nghiêm túc trong việc thảo luận mang tính xây dựng.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Biến nguồn mở thành một nơi hạnh phúc hơn"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f)
  </p>
</aside>

Cuối cùng, một bộ quy tắc ứng xử giúp đặt ra các quy tắc cơ bản cho hành vi cho những người tham gia dự án của bạn. Điều này đặc biệt có giá trị nếu bạn khởi chạy một dự án nguồn mở cho cộng đồng hoặc công ty. Một bộ quy tắc cho phép bạn tạo điều kiện cho hành vi cộng đồng lành mạnh, mang tính xây dựng, điều này sẽ làm giảm căng thẳng của bạn như một người duy trì.

Để biết thêm thông tin, hãy xem [Hướng dẫn về Quy tắc Ứng xử] của chúng tôi(../code-of-conduct/).

Ngoài việc truyền đạt _how_ bạn mong đợi người tham gia cư xử, một bộ quy tắc ứng xử cũng có xu hướng mô tả những người mà những kỳ vọng này áp dụng cho ai, khi họ áp dụng và phải làm gì nếu vi phạm xảy ra.

Giống như giấy phép nguồn mở, cũng có các tiêu chuẩn mới nổi về các quy tắc ứng xử, vì vậy bạn không phải tự viết. [Giao ước cộng tác viên] (https://continator-covenant.org/) là một bộ quy tắc ứng xử được sử dụng bởi [hơn 40.000 dự án nguồn mở] (https://www.continator-covenant.org/adopters ), bao gồm Kubernetes, Rails và Swift. Cho dù bạn sử dụng văn bản nào, bạn nên chuẩn bị để thực thi quy tắc ứng xử của mình khi cần thiết.

Dán văn bản trực tiếp vào tệp CODE_OF_CONDVEL trong kho lưu trữ của bạn. Giữ tệp trong thư mục gốc của dự án để dễ tìm và liên kết với tệp từ README của bạn.

## Đặt tên và xây dựng thương hiệu cho dự án của bạn

Thương hiệu không chỉ là một logo hào nhoáng hay tên dự án hấp dẫn. Đó là về cách bạn nói về dự án của bạn và người bạn tiếp cận với thông điệp của bạn.

### Chọn đúng tên

Chọn một cái tên dễ nhớ và, lý tưởng nhất, đưa ra một số ý tưởng về những gì dự án làm. Ví dụ:
* [Sentry](https://github.com/getsentry/sentry) giám sát các ứng dụng báo cáo sự cố
* [Thin](https://github.com/macournoyer/thin) là một máy chủ web Ruby nhanh và đơn giản

Nếu bạn đang xây dựng một dự án hiện có, sử dụng tên của họ làm tiền tố có thể giúp làm rõ những gì dự án của bạn làm (ví dụ, [node-fetch](https://github.com/bitinn/node-fetch) sử dụng `window.fetch` to Node.js).

Hãy xem xét rõ ràng tất cả những phần vừa nêu ở trên. Puns rất thú vị, nhưng hãy nhớ rằng một số trò đùa có thể không dịch sang các nền văn hóa khác hoặc những người có kinh nghiệm khác với bạn. Một số người dùng tiềm năng của bạn có thể là nhân viên công ty: bạn không muốn làm họ khó chịu khi họ phải giải thích dự án của bạn tại nơi làm việc!

### Tránh trùng lặp tên

[Kiểm tra các dự án nguồn mở có tên tương tự](http://ivantomic.com/projects/ospnc/), đặc biệt nếu bạn chia sẻ cùng ngôn ngữ hoặc hệ sinh thái. Nếu tên của bạn trùng lặp với một dự án phổ biến hiện có, bạn có thể nhầm lẫn đối tượng của mình.

Nếu bạn muốn một trang web, Twitter xử lý hoặc các thuộc tính khác đại diện cho dự án của bạn, hãy đảm bảo bạn có thể có được tên bạn muốn. Lý tưởng nhất là [bảo lưu những tên đó ngay bây giờ] (https://instantdomainsearch.com/) để yên tâm, ngay cả khi bạn chưa có ý định sử dụng chúng.

Đảm bảo rằng tên dự án của bạn không vi phạm bất kỳ nhãn hiệu có bản quyền nào. Một công ty có thể yêu cầu bạn gỡ bỏ dự án của bạn sau này, hoặc thậm chí có hành động pháp lý chống lại bạn. Nó chỉ không đáng để mạo hiểm.

Bạn có thể kiểm tra [Cơ sở dữ liệu thương hiệu toàn cầu của WIPO] (http://www.wipo.int/branddb/en/) để biết xung đột nhãn hiệu. Nếu bạn đang ở một công ty, đây là một trong những điều mà [nhóm pháp lý của bạn có thể giúp bạn](../legal/).

Cuối cùng, thực hiện tìm kiếm Google nhanh chóng cho tên dự án của bạn. Mọi người sẽ có thể dễ dàng tìm thấy dự án của bạn? Có cái gì khác xuất hiện trong kết quả tìm kiếm mà bạn không muốn họ nhìn thấy không?

### Cách bạn viết (và mã) cũng ảnh hưởng đến thương hiệu của bạn!

Trong suốt vòng đời dự án của bạn, bạn sẽ viết rất nhiều: READMEs, hướng dẫn, tài liệu cộng đồng, phản hồi các vấn đề, thậm chí có thể là bản tin và danh sách gửi thư.

Cho dù đó là tài liệu chính thức hay một email thông thường, phong cách viết của bạn là một phần của thương hiệu dự án của bạn. Xem xét cách bạn có thể bắt gặp đối tượng của mình và liệu đó có phải là giai điệu bạn muốn truyền tải.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/janl?s=180" class="pquote-avatar" alt="avatar">
 Tôi đã cố gắng tham gia với mọi chủ đề trong danh sách gửi thư, và thể hiện hành vi mẫu mực, đối xử tốt với mọi người, coi trọng vấn đề của họ và cố gắng trở nên hữu ích chung. Sau một thời gian, mọi người bị mắc kẹt không chỉ đặt câu hỏi mà còn giúp trả lời, và với sự hài lòng hoàn toàn của tôi, họ bắt chước phong cách của tôi.
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["Sustainable Open Source"](https://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

Sử dụng ngôn ngữ toàn diện, ấm áp (chẳng hạn như "họ", ngay cả khi đề cập đến người độc thân) có thể đi một chặng đường dài để làm cho dự án của bạn cảm thấy được chào đón những người đóng góp mới. Bám sát ngôn ngữ đơn giản, vì nhiều người đọc của bạn có thể không phải là người nói tiếng Anh bản ngữ.

Ngoài cách bạn viết từ, phong cách mã hóa của bạn cũng có thể trở thành một phần của thương hiệu dự án của bạn. [Angular] (https://angular.io/guide/styleguide) và [jQuery] (https://contribution.jquery.org/style-guide/js/) là hai ví dụ về các dự án có hướng dẫn và kiểu mã hóa nghiêm ngặt.

Không cần thiết phải viết hướng dẫn về phong cách cho dự án của bạn khi bạn mới bắt đầu và bạn có thể thấy rằng bạn thích kết hợp các phong cách mã hóa khác nhau vào dự án của mình. Nhưng bạn nên dự đoán cách viết và phong cách mã hóa của bạn có thể thu hút hoặc không khuyến khích các loại người khác nhau. Các giai đoạn sớm nhất của dự án là cơ hội của bạn để thiết lập tiền lệ mà bạn muốn thấy.

## Danh sách kiểm tra trước khi ra mắt của bạn

Sẵn sàng để mở nguồn dự án của bạn? Đây là một danh sách kiểm tra để giúp đỡ. Kiểm tra tất cả các hộp? Bạn đã sẵn sàng để đi! [Nhấp vào "xuất bản"] (https://help.github.com/articles/making-a-private-reposeective-public/) và vỗ nhẹ vào lưng bạn.

**Tài liệu**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    Dự án có file LICENSE với giấy phép nguồn mở
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    Dự án có tài liệu cơ bản (README, HƯỚNG DẪN, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    Tên dự án dễ nhớ, cho một số ý tưởng về những gì dự án làm và không bị trùng lặp với một dự án hiện có hoặc vi phạm nhãn hiệu
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    Hàng đợi các vấn đề đều được cập nhật mới nhất, được tổ chức và dán nhãn rõ ràng
  </label>
</div>

**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    Dự án sử dụng các quy ước mã nhất quán và tên hàm / phương thức / biến rõ ràng
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    Các quy tắc được nhận xét rõ ràng, ghi lại ý định và trường hợp
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    Không có tài liệu nhạy cảm trong lịch sử sửa đổi, các vấn đề hoặc yêu cầu kéo (ví dụ: mật khẩu hoặc thông tin không công khai khác)
  </label>
</div>

**Con người**

Nếu bạn là một cá nhân:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  Bạn đã nói chuyện với bộ phận pháp lý và / hoặc hiểu chính sách IP và nguồn mở của công ty bạn (nếu bạn là nhân viên)
  </label>
</div>

Nếu bạn là một công ty hoặc tổ chức:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    Bạn đã nói chuyện với bộ phận pháp lý của bạn
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    Bạn có một kế hoạch tiếp thị để thông báo và quảng bá dự án
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    Ai đó cam kết quản lý các tương tác cộng đồng (phản hồi các vấn đề, xem xét và hợp nhất các yêu cầu)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    Ít nhất hai người có quyền truy cập quản trị vào dự án
  </label>
</div>

## Bạn làm được rồi!

Chúc mừng dự án nguồn mở đầu tiên của bạn. Dù kết quả như thế nào, thì việc bạn công khai dự án của mình là một phần quà cho cộng đồng. Với mỗi cam kết, nhận xét và yêu cầu, bạn đang tạo cơ hội cho bản thân và cho người khác được học hỏi và phát triển.
