__Video: Các bước để thiết lập một ứng dụng Facebook__

<iframe width="560" height="315" src="https://www.youtube.com/embed/2xt8w-yQHgk" frameborder="0" allowfullscreen></iframe>
<br /><br />
__Để tạo một ứng dụng trên Facebook, hãy làm theo các bước sau:__

1. Đăng nhập vào [Facebook](http://www.facebook.com) và đi đến trang [Facebook Developer Page](https://developers.facebook.com/quickstarts/?platform=web) để tạo ứng dụng.
2. Điền các thông tin cần thiết và nhấn nút "Create New Facebook App ID" / "Tạo ID ứng dụng Facebook mới".
    <div class="soclall-br"></div>
    ![Facebook : Create App name](/img/facebook-1-create-app-name.JPG)
    <div class="soclall-br"></div>
3. Chọn bất kỳ một "Category" / "Danh mục" và nhấn nút "Create App ID" / "Tạo ID ứng dụng".
    <div class="soclall-br"></div>
    ![Facebook : Select Any Category](/img/facebook-2-select-any-category.JPG)
    <div class="soclall-br"></div>
4. Nhấn nút "Skip Quick Start" và đi đến trang quản lí ứng dụng.
5. Chọn mục "Settings" / "Cài đặt", nhấn nút "+ Add Platform" / "+ Thêm Nền tảng" ---> chọn "Website" / "Trang web" ---> điền theo các thông tin bên dưới:
    * App Domains / Miền ứng dụng: __api2.socialall.io__
    * Site URL / URL trang web: __https://api2.socialall.io/callback__  

    ![Facebook : Setting Page](/img/facebook-3-setting-page.JPG)
    <div class="soclall-br"></div>

6. Sau khi hoàn thành, nhấn nút "Save Changes" / "Lưu thay đổi".   
7. Chọn mục "App Review" / "Xét duyệt ứng dụng", và tại mục đầu tiên, nhấn vào nút để chuyển "O" sang "I" (hoặc chuyển "No" sang "Yes"). 
    <div class="soclall-br"></div>
    ![Facebook : Status Page](/img/facebook-4-status-page.jpg)
    <div class="soclall-br"></div>    
8. Tại trang "Settings" / "Cài đặt", bạn có thể thấy "App ID" / "ID ứng dụng" và "App Secret" / "Khóa ứng dụng". Để có thể lấy "App Secret" / "Khóa ứng dụng", bạn nhấn nút "Show" / "Hiển thị" ---> điền vào Mật khẩu của tài khoản Facebook của bạn.
    <div class="soclall-br"></div>
    ![Facebook : Get Api](/img/facebook-5-get-api.jpg)
    <div class="soclall-br"></div>
9. Tại trang SocialAll, bạn chọn tab "Networks" ---> chọn "Facebook" ---> bạn chép "App ID" / "ID ứng dụng", "App Secret" / "Khóa ứng dụng" và điền vào như hình bên dưới:
    <div class="soclall-br"></div>
    ![Facebook : Config Api](/img/facebook-6-config-api.jpg)
    <div class="soclall-br"></div>
10. Sau cùng, bạn nhấn nút "Save".

__Cách để gửi bản xét duyệt những tính năng không có sẵn trong ứng dụng Facebook:__

1. Tại trang "Facebook Developer", chọn ứng dụng Facebook mà bạn muốn thêm tính năng để xét duyệt. Sau đó, chọn mục "App Review" / "Xét duyệt ứng dụng" ---> Trong mục "Submit Items for Approval" / "Nộp các mục để duyệt", nhấn nút "Start a Submission" / "Bắt đầu gửi".
    <div class="soclall-br"></div>
    ![Facebook : Start Review](/img/facebook-7-start-review.jpg)
    <div class="soclall-br"></div>
2. Trong phần "LOGIN PERMISSIONS" / "QUYỀN ĐĂNG NHẬP", chọn những tính năng như sau: 
    * chọn __publish_actions__ nếu muốn sử dụng chức năng "SocialAll Posting".
    * chọn __user_photos__ nếu muốn sử dụng chức năng "SocialAll Photos".
    
    ![Facebook : Select Action](/img/facebook-8-select-action.jpg)
    <div class="soclall-br"></div>
    
3. Sau khi chọn xong, nhấn nút "Add Item" / "Thêm mục". Như hình dưới đây, bạn phải hoàn thành những yêu cầu trong phần "Before you can submit for review, complete the following:" / "Trước khi bạn có thể gửi để xét duyệt, hãy hoàn tất phần sau:" trước khi tiến hành bước tiếp theo. Sau khi bạn hoàn thành những yêu cầu đó, tiếp tục nhấn vào "Edit Notes" / "Chỉnh sửa ghi chú" của từng tính năng mà bạn đã chọn.
    <div class="soclall-br"></div>
    ![Facebook : Review Settings](/img/facebook-9-review-settings.jpg)
    <div class="soclall-br"></div>
4. Đối với tính năng __publish_actions__, phần chỉnh sửa ghi chú thực hiện như sau:
    * Chọn tất cả những mục trong phần "To get approved for publish_actions, please confirm that your app follows these policies:" / "Để được phê duyệt publish_actions, vui lòng xác nhận rằng ứng dụng của bạn tuân thủ các chính sách sau:".
    * Trong phần "How is your app using publish_actions?" / "Ứng dụng của bạn dùng publish_actions như thế nào?" : chọn __Lets people post to Facebook using a custom composer__ / __Cho phép mọi người đăng lên Facebook bằng trình biên soạn tùy chỉnh__
    * Trong phần "What platforms does your app use publish_actions on?" / "Ứng dụng của bạn dùng publish_actions trên nền tảng nào?" : chọn __Web__, chuyển __Off__ thành __On__ (hoặc chuyển __Tắt__ thành __Bật__)
    * Tiếp theo điền vào cách thức mà "Socialall Posting" hoạt động trên trang web của bạn.
    * Song song đó bạn cũng quay một video quay lại những bước mà "Socialall Posting" hoạt động trên trang web của bạn, rồi nhấn "Choose a file to upload..." / "Chọn một tệp để tải lên..." để tải video đó lên.
    * Hoàn thành những bước trên, cuối cùng bạn nhấn nút "Save" / "Lưu".
    
    ![Facebook : Edit Notes of publish_actions](/img/facebook-10-publish-edit-notes.jpg)
    <div class="soclall-br"></div>
    
5. Để gửi bản xét duyệt này, bạn nhấn nút "Submit For Review" / "Gửi để xét duyệt".