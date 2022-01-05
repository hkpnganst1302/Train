# **TÌM HIỂU NHANH VỀ GitHub**
## **1. Hello word**
Github là một nền tảng lưu trữ mã để kiểm soát phiên bản và sự cộng tác. Nó cho phép bạn và những người khác có thể làm chung các dự án từ khắp mọi nơi.
###      **- Tạo kho lưu trữ (Repository)**
Một kho lưu trữ thường được sử dụng để tổ chức lưu trữ một dự án. Kho lưu trữ có thể chứa thư mục, tệp, hình ảnh, video, tập dữ liệu và bảng tính (Bất cứ thứ gì mà dự án của bạn cần). Thông thường trong kho lưu trữ sẽ bao gồm tệp `README`, tệp chứa thông tin về dự án. Github giúp bạn dễ thực hiện tạo thêm một kho lưu trữ cùng lúc với khi tạo kho lưu trữ mới. Đồng thời nó cũng cung cấp các tùy chọn phổ biến khác như tệp giấy phép.

Kho lưu trữ `hello-word` có thể là nơi lưu trữ các ý tưởng, tài nguyên hoặc có thể chia sẻ và thảo luận mọi thứ với những người khác.

>*Lưu ý* : Bạn có thể tạo kho lưu trữ công khai cho một dự án nguồn mở. Khi tạo kho lưu trữ công cộng của bạn, hãy đảm bảo bao gồm tệp giấy phép xác định cách bạn muốn chia sẻ dự án của mình với người khác. Để biết thêm thông tin về nguồn mở, cụ thể là cách tạo và phát triển một dự án nguồn mở, chúng tôi đã tạo Hướng dẫn nguồn mở sẽ giúp bạn nuôi dưỡng một cộng đồng nguồn mở lành mạnh bằng cách đề xuất các phương pháp hay nhất để tạo và duy trì kho lưu trữ cho dự án nguồn mở của bạn. Bạn cũng có thể tham gia khóa học GitHub Learning Lab miễn phí về duy trì cộng đồng nguồn mở.

Các bước tạo kho lưu trữ (Repository):
- Bước 1: Tại góc trên bên phải của trang bất kỳ trong Github, sử dụng menu thả xuống và chọn **New repository**

    ![Hình ảnh tạo kho lưu trữ](./images/new-repository.png)
- Bước 2: Tại hộp **Repository name**, nhập `hello-word`.
- Bước 3: Tại hộp **Description**, viết đoạn mô tả ngắn.
- Bước 4: Chọn **Add** a README file.
- Bước 5: Chọn **Create repository**.
    ![Hình ảnh tạo kho lưu trữ](./images/new-repository-1.png)

###      **- Tạo nhánh (Branch)**
Việc phân nhánh cho phép bạn có các phiên bản khác nhau của kho lưu trữ trong cùng một lúc. Theo mặc định, kho lưu trữ sẽ có một nhánh chính `main` được coi là nhánh cuối cùng. Bạn có thể sử dụng các nhánh để thử nghiệm và thực hiện chỉnh sửa trước khi chuyển thành nhánh chính.

Khi tạo một nhánh ngoài nhánh chính, bạn đang tạo 1 bản sao hoặc ảnh chụp nhanh của nhánh chính tại thời điểm đó. Nếu có ai đó đã thay đổi đối với nhánh chính trong khi bạn đang làm việc với nhánh của mình thì bạn có thể lấy các bản cập nhất đó.

Sơ đồ này cho thấy:
*	Nhánh chính.

*	Nhánh mới là nhánh `tính năng`(feature).

*	Tiến trình nhánh tính năng thực hiện trước khi hợp nhất với nhánh chính.

    ![Hình ảnh branch](./images/branch.png)

Tại Github, các nhà phát triển, nhà văn và các nhà thiết kế có thể sử dụng các nhánh chính để lưu giữ các các bản sửa lỗi và các tính năng riêng lẻ với nhánh chính. Khi thay đổi đã sẵn sàng, họ thực hiện hợp nhất thành nhánh chính. 

Các bước tạo chi nhánh:

- Bước 1: Chọn vào tab **Code** của kho lưu trữ hello-world.
- Bước 2: Chọn vào menu thả xuống đầu danh sách tệp có nội dung chính.

    ![Hình ảnh main](./images/main.png)

- Bước 3: Nhập tên chi nhánh `readme-edits` vào hộp văn bản.

    ![Hình ảnh tạo readme-edits](./images/readme-edits.png)

- Bước 4: Chọn vào **Create branch:readme-edits from main**.

Sau khi thực hiện xong, hiện tại bạn sẽ có 2 nhánh: nhánh chính `main` và nhánh `readme-edits`. Hiện tại, trong chúng sẽ giống hết nhau. Tiếp theo bạn cần thay đổi vào chi nhánh mới.

###      **- Thực hiện và cam kết thay đổi (Making and commit changes)**
Khi đã thực hiện việc tạo một nhánh mới, Github sẽ đưa bạn đến trang mã cho chi nhánh mới đó, đây là một bản sao của main.

Bạn có thể thực hiện và lưu thay đổi đối với các tệp trong kho lưu trữ của bạn. Trên Github, các thay đổi đã lưu được gọi là cam kết (commits). Mỗi cam kết sẽ có một thông báo cam kết liên quan và mô tả giải thích cụ thể lý do tại sao có sự thay đổi. Thông báo cam kết ghi lại lịch sử các thay đổi của bạn để những người đóng góp khác có thể hiểu bạn đã làm gì và tại sao.

- Bước 1: Chọn tệp `README.md`.
- Bước 2: Chọn biểu tượng **Edit this file** để chỉnh sửa.
- Bước 3: Trong phần editor hãy viết một chút về bản thân.
- Bước 4: Trong hộp thoại **Commit changes**, viết thông báo cam kết mô tả sự thay đổi.
- Bước 5: Chọn **Commit changes**.

![Hình ảnh commit changes](./images/commit-changes.PNG)

Những thay đổi này sẽ chỉ được thực hiện đối với tệp README trên nhánh `readme-edits` của bạn, vì vậy bây giờ nhánh này chứa nội dung khác với nhánh chính.

### **- Tạo 1 pull request**
Có những thay đổi trong 1 nhánh ngoài nhánh main, bạn có thể mở 1 **pull request**.

**Pull request** là trọng tâm của sự hợp tác trên GitHub. Khi bạn mở 1 Pull request, bạn đề xuất các thay đổi của mình và yêu cầu ai đó xem xét và thu hút đóng góp của bạn, hợp nhất chúng vào nhánh của họ. Các pull request hiển thị sự khác biệt hoặc khác biệt về nội dung từ cả hai nhánh. Các thay đổi, cộng và trừ được hiển thị bằng các màu khác nhau.

Ngay sau khi bạn thực hiện một cam kết, bạn có thể mở một pull request và bắt đầu thảo luận, ngay cả trước khi mã hoàn tất.

Bằng cách sử dụng `@mention` của GitHub trong thông báo pull request, bạn có thể yêu cầu phản hồi từ những người hoặc nhóm cụ thể, cho dù họ ở dưới sảnh hay cách xa bạn 10 múi giờ.
- Bước 1: Chọn **Pull requests** của kho lưu trữ `hello-world`.
- Bước 2: Chọn **New pull request**.
- Bước 3: Trong hộp **Example Comparisons** chọn nhánh đã thực hiện `readme-edits`, để so sánh với nhánh chính `main` (the original).
- Bước 4: Xem lại những thay đổi của bạn trong các điểm khác biệt trên trang Compare, đảm bảo rằng chúng là những gì bạn muốn gửi.

    ![Hình ảnh compare](./images/compare.PNG)

- Bước 5: Chọn **Create pull request**.
- Bước 6: Đặt tiêu đề cho pull request và viết mô tả ngắn gọn về các thay đổi. Bạn có thể sử dụng biểu tượng cảm xúc, kéo và thả hình ảnh, gif.
- Bước 7: Chọn **Create pull request**.

Các cộng tác viên của bạn hiện có thể xem xét các chỉnh sửa của bạn và đưa ra đề xuất.
### **- Hợp nhất pull request của bạn**
Trong bước cuối cùng này, bạn sẽ hợp nhất nhánh readme-edits của mình vào nhánh chính.
- Bước 1: Chọn **Merge pull requets** để hợp nhất thành nhánh chính `main`.
- Bước 2: Chọn **Confirm merge**.
- Bước 3: Hãy tiếp tục và xóa chi nhánh, vì các thay đổi của nó đã được kết hợp, bằng cách nhấp vào **Delete branch**.

## **2. Thiết lập GitHub**
### Trung tâm của GitHub là một hệ thống kiểm soát phiên bản mã nguồn mở (VCS) được gọi là Git. Git chịu trách nhiệm về mọi thứ liên quan đến GitHub xảy ra cục bộ trên máy tính của bạn.
### **- Sử dụng Git**
Để sử dụng Git trên dòng lệnh, bạn cần tải xuống, cài đặt và định cấu hình Git trên máy tính của mình. Bạn cũng có thể cài đặt GitHub CLI để sử dụng GitHub từ dòng lệnh. Để biết thêm thông tin, hãy xem "[Giới thiệu về GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli)".

Nếu bạn muốn làm việc với Git cục bộ, nhưng không muốn sử dụng dòng lệnh, thay vào đó, bạn có thể tải xuống và cài đặt ứng dụng GitHub Desktop. Để biết thêm thông tin, hãy xem "[Cài đặt và định cấu hình GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop)".

Nếu bạn không cần làm việc với các tệp cục bộ, GitHub cho phép bạn hoàn thành nhiều tác vụ liên quan đến Git trực tiếp trong trình duyệt, bao gồm:
- Tạo kho lưu trữ.
- Quản lý tệp.
- 

### **- Cài đặt GitHub**
- Bước 1. [Tải xuống và cài đặt phiên bản mới nhất của Git](https://git-scm.com/downloads).
- Bước 2: [Đặt tên người dùng của bạn trong Git](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git).
- Bước 3: [Đặt địa chỉ email cam kết của bạn trong Git](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address)

### **- Tiếp theo, xác thực với GitHub từ Git**
Khi bạn kết nối với kho lưu trữ GitHub từ Git, bạn sẽ cần xác thực với GitHub bằng HTTPS hoặc SSH.

>*Note* : Bạn có thể xác thực với GitHub bằng GitHub CLI, cho HTTP hoặc SSH. Để biết thêm thông tin, hãy xem đăng nhập `gh auth login`.

- Kết nối qua HTTPS (khuyến nghị)

    Nếu bạn sao chép bằng HTTPS, bạn có thể lưu thông tin đăng nhập GitHub của mình trong Git bằng cách sử dụng trình trợ giúp thông tin xác thực.
- Kết nối qua SSH

    Nếu bạn sao chép bằng SSH, bạn phải tạo khóa SSH trên mỗi máy tính mà bạn sử dụng để đẩy hoặc kéo từ GitHub.

## **3. Bản sao kho lưu trữ (Fork a repo)**
### Một Fork là một bản sao của một kho lưu trữ. Tạo kho lưu trữ cho phép bạn tự do thử nghiệm với các thay đổi mà không ảnh hưởng đến dự án ban đầu.
### **- Giới thiệu về Forks**
Thông thường nhất, fork được sử dụng để đề xuất các thay đổi đối với dự án của người khác hoặc sử dụng dự án của người khác làm điểm khởi đầu cho ý tưởng của riêng bạn. Bạn có thể phân nhánh một kho lưu trữ để tạo một bản sao của kho lưu trữ và thực hiện các thay đổi mà không ảnh hưởng đến kho lưu trữ ngược dòng. Để biết thêm thông tin, hãy xem "[Làm việc với forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks)".

### **- Đề xuất các thay đổi đối với dự án của người khác**
*Ví dụ* : bạn có thể sử dụng fork để đề xuất các thay đổi liên quan đến việc sửa lỗi. Thay vì ghi lại sự cố cho một lỗi bạn đã tìm thấy, bạn có thể:
- Fork kho lưu trữ.
- Thực hiện sửa lỗi.
- Gửi 1 pull request tới chủ dự án.

### **- Sử dụng dự án của người khác để khởi đầu cho ý tưởng của mình**
Phần mềm nguồn mở dựa trên ý tưởng rằng bằng cách chia sẻ mã, chúng ta có thể tạo ra phần mềm tốt hơn, đáng tin cậy hơn. Để biết thêm thông tin, hãy xem "[Giới thiệu về sáng kiến ​​nguồn mở (About the Open Source Initiative)](https://opensource.org/about) " trên sáng kiến ​​nguồn mở (Open Source Initiative).

Để biết thêm thông tin về việc áp dụng các nguyên tắc nguồn mở vào công việc phát triển của tổ chức của bạn trên GitHub.com, hãy xem sách trắng của GitHub "[Giới thiệu về nguồn nội bộ (An introduction to innersource)](https://resources.github.com/whitepapers/introduction-to-innersource/)".

Khi tạo kho lưu trữ công khai của bạn từ một nhánh dự án của ai đó, hãy đảm bảo bao gồm tệp giấy phép xác định cách bạn muốn chia sẻ dự án của mình với người khác. Để biết thêm thông tin, hãy xem "[Chọn giấy phép nguồn mở (Choose an open source license)](https://choosealicense.com/)" tại selectalicense.com.

Để biết thêm thông tin về nguồn mở, cụ thể là cách tạo và phát triển một dự án nguồn mở, chúng tôi đã tạo [Hướng dẫn nguồn mở (Open Source Guides)](https://opensource.guide/) sẽ giúp bạn nuôi dưỡng một cộng đồng nguồn mở lành mạnh bằng cách đề xuất các phương pháp hay nhất để tạo và duy trì kho lưu trữ cho dự án nguồn mở của bạn. Bạn cũng có thể tham gia khóa học [GitHub Learning Lab](https://lab.github.com/) miễn phí về duy trì cộng đồng nguồn mở.
### **- Điều kiện tiên quyết (Prerequisites)**
Nếu bạn chưa có, trước tiên bạn nên [thiết lập Git](#2.Thiết-lập-GitHub). Đừng quên thiết lập xác thực cho GitHub.com từ Git.

[Bấm về đầu](#TÌM-HIỂU-NHANH-VỀ-GitHub)