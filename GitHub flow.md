# **Luồng GitHub (GitHub flow)**
## Theo dõi luồng GitHub để cộng tác trong các dự án
## **Giới thiệu (Introduction)**
Luồng GitHub là một luồng công việc dựa trên nhánh. Luồng GitHub hữu ích cho tất cả mọi người, không chỉ các nhà phát triển. Ví dụ: ở đây tại GitHub, chúng tôi sử dụng luồng GitHub cho [trang chính sách (site policy)](https://github.com/github/site-policy), trang [tài liệu(documentation)](https://github.com/github/docs) và [lộ trình (roadmap)](https://github.com/github/roadmap) của chúng tôi.
## **Theo dõi luồng GitHub (Following GitHub flow)**
### **Tạo một chi nhánh (Create a branch)**
Tạo một chi nhánh trong kho lưu trữ của bạn. Tên chi nhánh ngắn gọn, mang tính mô tả cho phép các cộng tác viên của bạn xem nhanh công việc đang diễn ra. Ví dụ: tăng thời gian chờ kiểm tra hoặc thêm quy tắc ứng xử. Để biết thêm thông tin, hãy xem "[Tạo và xóa các nhánh trong kho lưu trữ của bạn (Creating and deleting branches within your repository)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)."

Bằng cách tạo một nhánh, bạn tạo một không gian để làm việc mà không ảnh hưởng đến nhánh mặc định. Ngoài ra, bạn cho các cộng tác viên cơ hội đánh giá công việc của bạn.

### **Thực hiện thay đổi (Make changes)**
Trên chi nhánh của bạn, thực hiện bất kỳ thay đổi mong muốn nào đối với kho lưu trữ. Để biết thêm thông tin, xem "[Tạo tệp mới (Creating new files)](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)", "[Chỉnh sửa tệp (Editing files)](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)", "[Đổi tên tệp (Renaming a file)](https://docs.github.com/en/repositories/working-with-files/managing-files/renaming-a-file)", "[Di chuyển tệp đến một vị trí mới(Moving a file to a new location)](https://docs.github.com/en/repositories/working-with-files/managing-files/moving-a-file-to-a-new-location)" or "[Xóa tệp trong kho lưu trữ (Deleting files in a repository)](https://docs.github.com/en/repositories/working-with-files/managing-files/deleting-files-in-a-repository)".

Chi nhánh của bạn là một nơi an toàn để thực hiện các thay đổi. Nếu bạn mắc lỗi, bạn có thể hoàn nguyên các thay đổi của mình hoặc đẩy các thay đổi bổ sung để sửa lỗi. Các thay đổi của bạn sẽ không kết thúc trên nhánh mặc định cho đến khi bạn hợp nhất nhánh của mình.

Cam kết và đẩy các thay đổi của bạn đến chi nhánh của bạn. Cung cấp cho mỗi cam kết một thông điệp mô tả để giúp bạn và những người đóng góp trong tương lai hiểu những gì thay đổi trong cam kết. Ví dụ, `fix typo` or `increase rate limit`.

Lý tưởng nhất là mỗi cam kết chứa một thay đổi hoàn toàn, riêng biệt. Điều này giúp bạn dễ dàng hoàn nguyên các thay đổi nếu bạn quyết định thực hiện một cách tiếp cận khác. Ví dụ: nếu bạn muốn đổi tên một biến và thêm một số thử nghiệm, hãy đặt đổi tên biến trong một cam kết và các thử nghiệm trong một cam kết khác. Sau đó, nếu bạn muốn giữ lại các thử nghiệm nhưng hoàn nguyên đổi tên biến, bạn có thể hoàn nguyên cam kết cụ thể chứa đổi tên biến. Nếu bạn đặt đổi tên biến và các thử nghiệm trong cùng một cam kết hoặc trải rộng việc đổi tên biến trên nhiều cam kết, bạn sẽ tốn nhiều công sức hơn để hoàn nguyên các thay đổi của mình.

Bằng cách cam kết và đẩy các thay đổi của mình, bạn sao lưu công việc của mình vào bộ nhớ từ xa. Điều này có nghĩa là bạn có thể truy cập công việc của mình từ bất kỳ thiết bị nào. Điều đó cũng có nghĩa là các cộng tác viên của bạn có thể xem công việc của bạn, trả lời câu hỏi và đưa ra đề xuất hoặc đóng góp.

Tiếp tục thực hiện, cam kết và đẩy các thay đổi đối với chi nhánh của bạn cho đến khi bạn sẵn sàng yêu cầu phản hồi.

> Mẹo: Tạo một nhánh riêng cho từng nhóm thay đổi không liên quan. Điều này giúp người đánh giá đưa ra phản hồi dễ dàng hơn. Nó cũng giúp bạn và các cộng tác viên trong tương lai hiểu các thay đổi dễ dàng hơn và hoàn nguyên hoặc xây dựng dựa trên chúng. Ngoài ra, nếu có sự chậm trễ trong một tập hợp các thay đổi, thì các thay đổi khác của bạn cũng không bị trì hoãn.

### **Tạo một yêu cầu kéo (Create a pull request)**
Tạo một yêu cầu kéo để yêu cầu cộng tác viên phản hồi về các thay đổi của bạn. Xem xét yêu cầu kéo có giá trị đến mức một số kho lưu trữ yêu cầu xem xét phê duyệt trước khi yêu cầu kéo có thể được hợp nhất. Nếu bạn muốn có phản hồi hoặc lời khuyên sớm trước khi hoàn thành các thay đổi của mình, bạn có thể đánh dấu yêu cầu kéo của mình dưới dạng bản nháp. Để biết thêm thông tin.

Khi bạn tạo một yêu cầu kéo, hãy bao gồm bản tóm tắt các thay đổi và chúng giải quyết vấn đề gì. Bạn có thể bao gồm hình ảnh, liên kết và bảng để giúp truyền đạt thông tin này. Nếu yêu cầu kéo của bạn giải quyết một vấn đề, hãy liên kết vấn đề để các bên liên quan đến vấn đề biết về yêu cầu kéo và ngược lại. Nếu bạn liên kết với một từ khóa, sự cố sẽ tự động đóng lại khi kết hợp yêu cầu kéo. Để biết thêm thông tin xem [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) và [Linking a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)

![abc](./images/1.PNG)

Ngoài việc điền vào nội dung của yêu cầu kéo, bạn có thể thêm nhận xét vào các dòng cụ thể của yêu cầu kéo để chỉ ra một cách rõ ràng điều gì đó cho người đánh giá.

![abc](./images/2.PNG)

Kho lưu trữ của bạn có thể được định cấu hình để tự động yêu cầu xem xét từ các nhóm hoặc người dùng cụ thể khi một yêu cầu kéo được tạo. Bạn cũng có thể @mention theo cách thủ công hoặc yêu cầu đánh giá từ những người hoặc nhóm cụ thể.

Nếu kho lưu trữ của bạn có các kiểm tra được định cấu hình để chạy trên các yêu cầu kéo, bạn sẽ thấy bất kỳ kiểm tra nào không thành công đối với yêu cầu kéo của bạn. Điều này giúp bạn bắt lỗi trước khi hợp nhất chi nhánh của mình. Để biết thêm thông tin xem "[About status checks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks)".

### **Địa chỉ nhận xét đánh giá (Address review comments)**
Người phản biện nên để lại câu hỏi, nhận xét và đề xuất. Người đánh giá có thể nhận xét về toàn bộ yêu cầu kéo hoặc thêm nhận xét vào các dòng cụ thể. Bạn và người đánh giá có thể chèn hình ảnh hoặc mã đề xuất để làm rõ nhận xét. Để biết thêm thông tin hãy xem "[Reviewing changes in pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests)"

### **Hợp nhất yêu cầu kéo của bạn (Merge your pull request)**
Khi yêu cầu kéo của bạn được chấp thuận, hãy hợp nhất yêu cầu kéo của bạn. Thao tác này sẽ tự động hợp nhất chi nhánh của bạn để các thay đổi của bạn xuất hiện trên chi nhánh mặc định. GitHub lưu giữ lịch sử nhận xét và cam kết trong yêu cầu kéo để giúp những người đóng góp trong tương lai hiểu được những thay đổi của bạn. Để biết thêm thông tin, xem "[Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)".

GitHub sẽ cho bạn biết nếu yêu cầu kéo của bạn có xung đột cần được giải quyết trước khi hợp nhất. Để biết thêm thông tin, xem "[Addressing merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts)".

Cài đặt bảo vệ nhánh có thể chặn việc hợp nhất nếu yêu cầu kéo của bạn không đáp ứng các yêu cầu nhất định. Ví dụ: bạn cần một số đánh giá phê duyệt nhất định hoặc đánh giá phê duyệt từ một nhóm cụ thể. Để biết thêm thông tin, "[About protected branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)"

### **Xóa chi nhánh của bạn (Delete your branch)**
Sau khi bạn hợp nhất yêu cầu kéo của mình, hãy xóa nhánh của bạn. Điều này cho thấy rằng công việc trên nhánh đã hoàn thành và ngăn bạn hoặc những người khác vô tình sử dụng các nhánh cũ. Để biết thêm thông tin, hãy xem "[Deleting and restoring branches in a pull request](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/deleting-and-restoring-branches-in-a-pull-request)".

Đừng lo lắng về việc mất thông tin. Yêu cầu kéo và lịch sử cam kết của bạn sẽ không bị xóa. Bạn luôn có thể khôi phục nhánh đã xóa của mình hoặc hoàn nguyên yêu cầu kéo của mình nếu cần.