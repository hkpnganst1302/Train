# **Bản sao kho lưu trữ (Fork a repo)**
## Một Fork là một bản sao của một kho lưu trữ. Tạo kho lưu trữ cho phép bạn tự do thử nghiệm với các thay đổi mà không ảnh hưởng đến dự án ban đầu.
## **Giới thiệu về Forks (About forks)**
Thông thường nhất, fork được sử dụng để đề xuất các thay đổi đối với dự án của người khác hoặc sử dụng dự án của người khác làm điểm khởi đầu cho ý tưởng của riêng bạn. Bạn có thể phân nhánh một kho lưu trữ để tạo một bản sao của kho lưu trữ và thực hiện các thay đổi mà không ảnh hưởng đến kho lưu trữ ngược dòng. Để biết thêm thông tin, hãy xem "[Làm việc với forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks)".

## **Đề xuất các thay đổi đối với dự án của người khác (Propose changes to someone else's project)**
*Ví dụ* : bạn có thể sử dụng fork để đề xuất các thay đổi liên quan đến việc sửa lỗi. Thay vì ghi lại sự cố cho một lỗi bạn đã tìm thấy, bạn có thể:
- Fork kho lưu trữ.
- Thực hiện sửa lỗi.
- Gửi 1 pull request tới chủ dự án.

## **Sử dụng dự án của người khác để khởi đầu cho ý tưởng của mình (Use someone else's project as a starting point for your own idea.)**
Phần mềm nguồn mở dựa trên ý tưởng rằng bằng cách chia sẻ mã, chúng ta có thể tạo ra phần mềm tốt hơn, đáng tin cậy hơn. Để biết thêm thông tin, hãy xem "[Giới thiệu về sáng kiến ​​nguồn mở (About the Open Source Initiative)](https://opensource.org/about) " trên sáng kiến ​​nguồn mở (Open Source Initiative).

Để biết thêm thông tin về việc áp dụng các nguyên tắc nguồn mở vào công việc phát triển của tổ chức của bạn trên GitHub.com, hãy xem sách trắng của GitHub "[Giới thiệu về nguồn nội bộ (An introduction to innersource)](https://resources.github.com/whitepapers/introduction-to-innersource/)".

Khi tạo kho lưu trữ công khai của bạn từ một nhánh dự án của ai đó, hãy đảm bảo bao gồm tệp giấy phép xác định cách bạn muốn chia sẻ dự án của mình với người khác. Để biết thêm thông tin, hãy xem "[Chọn giấy phép nguồn mở (Choose an open source license)](https://choosealicense.com/)" tại selectalicense.com.

Để biết thêm thông tin về nguồn mở, cụ thể là cách tạo và phát triển một dự án nguồn mở, chúng tôi đã tạo [Hướng dẫn nguồn mở (Open Source Guides)](https://opensource.guide/) sẽ giúp bạn nuôi dưỡng một cộng đồng nguồn mở lành mạnh bằng cách đề xuất các phương pháp hay nhất để tạo và duy trì kho lưu trữ cho dự án nguồn mở của bạn. Bạn cũng có thể tham gia khóa học [GitHub Learning Lab](https://lab.github.com/) miễn phí về duy trì cộng đồng nguồn mở.
## **Điều kiện tiên quyết (Prerequisites)**
Nếu bạn chưa có, trước tiên bạn nên [thiết lập Git](#Thiết-lập-GitHub). Đừng quên thiết lập xác thực cho GitHub.com từ Git.
## **Tạo kho lưu trữ sao chép(Forking a repository)**
Bạn có thể phân nhánh một dự án để đề xuất các thay đổi đối với kho lưu trữ ngược dòng hoặc bản gốc. Trong trường hợp này, bạn nên thường xuyên đồng bộ fork của mình với kho lưu trữ ngược dòng. Để làm điều này, bạn sẽ cần sử dụng Git trên dòng lệnh. Bạn có thể thực hành thiết lập kho lưu trữ ngược dòng bằng cách sử dụng cùng một kho lưu trữ [octocat / Spoon-Knife](https://github.com/octocat/Spoon-Knife) mà bạn vừa chia nhỏ.
- Bước 1: Trên GitHub.com, điều hướng đến kho lưu trữ [octocat / Spoon-Knife](https://github.com/octocat/Spoon-Knife).
- Bước 2: Ở dóc bên phải của trang, chọn **fork**.

    ![fork](./images/fork.PNG)

## **Nhân bản kho lưu trữ được phân nhánh(Cloning your forked repository)**
Ngay bây giờ, bạn có một nhánh của kho lưu trữ Spoon-Knife, nhưng bạn không có các tệp trong kho đó cục bộ trên máy tính của mình.
- Bước 1: Trên GitHub.com, điều hướng đến **your fork** kho lưu trữ Spoon-Knife.
- Bước 2: Phía trên danh sách các tệp, chọn **Code**.

    ![fork](./images/code.PNG)

- Bước 3: Để sao chép kho lưu trữ bằng HTTPS, trong "Sao chép bằng HTTPS", hãy nhấp vào ![coppy](./images/coppy.PNG). 
Để sao chép kho lưu trữ bằng khóa SSH, bao gồm chứng chỉ do cơ quan cấp chứng chỉ SSH của tổ chức bạn cấp, hãy nhấp vào **Use SSH**, sau đó chọn ![coppy](./images/coppy.PNG). Để sao chép kho lưu trữ bằng GitHub CLI, hãy nhấp vào Sử dụng **GitHub CLI**, sau đó nhấp vào ![coppy](./images/coppy.PNG).

    ![HTTPS](./images/clone-with-HTTPS.PNG)

    ![HTTPS](./images/clone.PNG)

- Bước 4: Mở Git Bash.
- Bước 5: Thay đổi thư mục làm việc hiện tại thành vị trí mà bạn muốn thư mục được nhân bản.
- Bước 6: Nhập `git clone`, rồi dán URL bạn đã sao chép trước đó. Nó sẽ giống như thế này, với tên người dùng GitHub của bạn thay vì `YOUR-USERNAME`:
        
        $git clone https://github.com/YOUR-USERNAME/Spoon-Knife

- Bước 7: Nhấn `Enter`. Bản sao cục bộ của bạn sẽ được tạo.
        
        $ git clone https://github.com/YOUR-USERNAME/Spoon-Knife
        > Cloning into `Spoon-Knife`...
        > remote: Counting objects: 10, done.
        > remote: Compressing objects: 100% (8/8), done.
        > remove: Total 10 (delta 1), reused 10 (delta 1)
        > Unpacking objects: 100% (10/10), done.
## **Định cấu hình Git để đồng bộ fork của bạn với kho lưu trữ ban đầu (Configuring Git to sync your fork with the original repository)**
Khi bạn fork một dự án để đề xuất các thay đổi đối với kho lưu trữ ban đầu, bạn có thể định cấu hình Git để kéo các thay đổi từ kho lưu trữ gốc hoặc ngược dòng vào bản sao cục bộ của fork của bạn.
- Bước 1. Trên GitHub.com, điều hướng đến kho lưu trữ [octocat/Spoon-Knife](https://github.com/octocat/Spoon-Knife).
- Bước 2. Phía trên danh sách các tệp, chọn **Code**.

    ![fork](./images/code.PNG)

- Bước 3. Để sao chép kho lưu trữ bằng HTTPS, trong "Clone with HTTPS",nhấp chọn ![coppy](./images/coppy.PNG). Để sao chép kho lưu trữ bằng khóa SSH, bao gồm chứng chỉ do cơ quan cấp chứng chỉ SSH của tổ chức bạn cấp, hãy nhấp vào**Use SSH**, sau đó nhấp vào ![coppy](./images/coppy.PNG). Để sao chép kho lưu trữ bằng GitHub CLI, hãy nhấp vào **Use GitHub CLI**, sau đó nhấp vào ![coppy](./images/coppy.PNG).

![HTTPS](./images/clone-with-HTTPS.PNG)

![HTTPS](./images/clone.PNG)

- Bước 4. Mở Git Bash.
- Bước 5. Thay đổi các thư mục đến vị trí của ngã ba mà bạn đã nhân bản.
        * Để đi đến thư mục chính của bạn, nhập `cd` mà không có văn bản nào khác.
        * Để liệt kê các tệp và thư mục trong thư mục hiện tại của bạn, nhập `ls`.
        * Để đi đến một trong các thư mục được liệt kê của bạn, nhập `cd your_listed_directory`.
        * Để truy cập một thư mục, `cd ..`
- Bước 6. Gõ `git remote -v` và nhấn **Enter**. Bạn sẽ thấy kho lưu trữ từ xa được định cấu hình hiện tại cho fork của mình.

            $ git remote -v
            > origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
            > origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
- Bước 7. Nhập `git remote add upstream`, sau đó dán URL bạn đã sao chép ở bước 2 và nhấn **Enter**. Nó sẽ trông giống thế này:

            $ git remote add upstream https://github.com/octocat/Spoon-Knife.git
- Bước 8. Để xác minh kho lưu trữ ngược dòng mới mà bạn đã chỉ định cho fork của mình, nhập `git remote -v`. Bạn sẽ thấy URL cho bản fork của mình là `origin` và URL cho kho lưu trữ gốc ở dạng `upstream`.

            $ git remote -v
            > origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
            > origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
            > upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (fetch)
            > upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (push)

Bây giờ, bạn có thể giữ cho fork của mình được đồng bộ hóa với kho lưu trữ ngược dòng bằng một vài lệnh Git. Để biết thêm thông tin, hãy xem "[Đồng bộ hóa một fork (Syscinga fork)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)".

Tiếp theo, bạn có thể thực hiện bất kỳ thay đổi nào đối với một ngã ba (fork), bao gồm:

* **Tạo các nhánh (Creating branches)**: Các [nhánh (Branches)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) cho phép bạn xây dựng các tính năng mới hoặc thử nghiệm các ý tưởng mà không khiến dự án chính của bạn gặp rủi ro.
* **Mở các yêu cầu kéo (Opening pull requests)**: Nếu bạn hy vọng đóng góp trở lại kho lưu trữ ban đầu, bạn có thể gửi yêu cầu đến tác giả gốc để kéo fork của bạn vào kho lưu trữ của họ bằng cách gửi [yêu cầu kéo (pull request)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
## **Tìm một kho lưu trữ khác để phân nhánh (Find another repository to fork)**
Tạo kho lưu trữ để bắt đầu đóng góp cho một dự án. Bạn có thể phân nhánh một kho lưu trữ vào tài khoản người dùng của mình hoặc bất kỳ tổ chức nào mà bạn có quyền tạo kho lưu trữ. Để biết thêm thông tin, hãy xem "[Vai trò trong tổ chức(Roles in an organization)](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization)".

Nếu bạn có quyền truy cập vào một kho lưu trữ riêng tư và chủ sở hữu cho phép phân nhánh, bạn có thể chuyển kho lưu trữ đó vào tài khoản người dùng của mình hoặc bất kỳ tổ chức nào trên Nhóm GitHub nơi bạn có quyền tạo kho lưu trữ. Bạn không thể chuyển một kho lưu trữ riêng cho một tổ chức bằng GitHub Free. Để biết thêm thông tin, hãy xem "[Sản phẩm của GitHub (GitHub's products)](https://docs.github.com/en/get-started/learning-about-github/githubs-products)."

Bạn có thể duyệt [Explore](https://github.com/explore) để tìm các dự án và bắt đầu đóng góp vào kho mã nguồn mở. Để biết thêm thông tin, hãy xem "[Tìm cách đóng góp cho nguồn mở trên GitHub (Finding ways to contribute to open source on GitHub)](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)".