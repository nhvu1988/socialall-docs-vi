__Để đăng kí 1 ứng dụng trên LinkedIn, vui lòng làm theo các bước sau:__

1. Đăng nhập vào [LinkedIn](https://www.linkedin.com/) và đi đến trang [LinkedIn App](https://www.linkedin.com/secure/developer) để tạo ứng dụng
    <div class="soclall-br"></div>
    ![Linkedin : List App](/img/linkedin-1-list-app.JPG)
    <div class="soclall-br"></div>
2. Ấn nút "Add New Application" và điền thông tin vào như dưới đây
    * Website URL: __http://soclall.com/__
3. Sau đó, chọn ô Agreement và nhấn nút "Submit".
    <div class="soclall-br"></div>
    ![Linkedin : Create App Form](/img/linkedin-2-create-app-form.jpg)
    <div class="soclall-br"></div>
4. Sau khi thành công tạo ứng dụng, chọn mục "Authentication" và đến trang "Authentication" .
5. Trong phần "Default Application Permissions", vui lòng kiểm tra:
    * r_basicprofile: if you want to use "SoclAll Login"
    * r_emailaddress: if you want to use "SoclAll Invite"
    * w_share: if you want to use "SoclAll Posting"
6. Tại phần "OAuth 2.0", điền phần "Authorized Redirect URLs" : __http://api.soclall.com/callback__ và ấn nút "Update".
    <div class="soclall-br"></div>
    ![Linkedin : Authentication Page](/img/linkedin-3-authentication-page.jpg)
    <div class="soclall-br"></div>    
7. Tại trang "Authentication" , bạn có thể lấy "Client ID" và "Client Secret" để điền vào SoclAll LinkedIn Settings form.