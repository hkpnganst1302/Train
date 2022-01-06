# **Thiết lập GitHub (Set up Git)**
## Trung tâm của GitHub là một hệ thống kiểm soát phiên bản mã nguồn mở (VCS) được gọi là Git. Git chịu trách nhiệm về mọi thứ liên quan đến GitHub xảy ra cục bộ trên máy tính của bạn.
## **Sử dụng Git (Using Git)**
Để sử dụng Git trên dòng lệnh, bạn cần tải xuống, cài đặt và định cấu hình Git trên máy tính của mình. Bạn cũng có thể cài đặt GitHub CLI để sử dụng GitHub từ dòng lệnh. Để biết thêm thông tin, hãy xem "[Giới thiệu về GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli)".

Nếu bạn muốn làm việc với Git cục bộ, nhưng không muốn sử dụng dòng lệnh, thay vào đó, bạn có thể tải xuống và cài đặt ứng dụng GitHub Desktop. Để biết thêm thông tin, hãy xem "[Cài đặt và định cấu hình GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop)".

Nếu bạn không cần làm việc với các tệp cục bộ, GitHub cho phép bạn hoàn thành nhiều tác vụ liên quan đến Git trực tiếp trong trình duyệt, bao gồm:
- Tạo kho lưu trữ.
- Quản lý tệp.
## **Cài đặt GitHub (Setting up Git)**
- Bước 1. [Tải xuống và cài đặt phiên bản mới nhất của Git](https://git-scm.com/downloads).
- Bước 2: [Đặt tên người dùng của bạn trong Git](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git).
- Bước 3: [Đặt địa chỉ email cam kết của bạn trong Git](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address)

## **Tiếp theo, xác thực với GitHub từ Git (Next steps: Authenticating with GitHub from Git)**
Khi bạn kết nối với kho lưu trữ GitHub từ Git, bạn sẽ cần xác thực với GitHub bằng HTTPS hoặc SSH.

>*Lưu ý* : Bạn có thể xác thực với GitHub bằng GitHub CLI, cho HTTP hoặc SSH. Để biết thêm thông tin, hãy xem đăng nhập `gh auth login`.

- Kết nối qua HTTPS (khuyến nghị)

    Nếu bạn sao chép bằng HTTPS, bạn có thể lưu thông tin đăng nhập GitHub của mình trong Git bằng cách sử dụng trình trợ giúp thông tin xác thực.
- Kết nối qua SSH

    Nếu bạn sao chép bằng SSH, bạn phải tạo khóa SSH trên mỗi máy tính mà bạn sử dụng để đẩy hoặc kéo từ GitHub.