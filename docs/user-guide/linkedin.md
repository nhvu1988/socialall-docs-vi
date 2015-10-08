__Để đăng kí một ứng dụng trên LinkedIn, vui lòng làm theo các bước sau:__

1. Đăng nhập vào [LinkedIn](https://www.linkedin.com/) và đi đến trang [LinkedIn App](https://www.linkedin.com/secure/developer) để tạo ứng dụng
    <div class="soclall-br"></div>
    ![Linkedin : List App](/img/linkedin-1-list-app.JPG)
    <div class="soclall-br"></div>
2. Ấn nút "Create Application" và điền theo thông tin dưới đây:
    * Website URL: __http://socialall.io/__
3. Sau đó, chọn ô "I have read and agree to the LinkedIn API Terms of Use" và nhấn nút "Submit".
    <div class="soclall-br"></div>
    ![Linkedin : Create App Form](/img/linkedin-2-create-app-form.jpg)
    <div class="soclall-br"></div>
4. Sau khi tạo ứng dụng thành công, chọn mục "Authentication".
5. Trong phần "Default Application Permissions", vui lòng chọn theo:
    * r_basicprofile: nếu bạn muốn sử dụng "SoclAll Login"
    * r_emailaddress: nếu bạn muốn sử dụng "SoclAll Invite"
    * w_share: nếu bạn muốn sử dụng "SoclAll Posting"
6. Tại phần "OAuth 2.0", điền vào "Authorized Redirect URLs" : __http://api2.socialall.io/callback__ và ấn nút "Add". Sau đó, điền lần nữa: __https://api2.socialall.io/callback__ và ấn nút "Add".
    <div class="soclall-br"></div>
    ![Linkedin : Authentication Page](/img/linkedin-3-authentication-page.jpg)
    <div class="soclall-br"></div>    
7. Cuối cùng, ấn nút "Update".
8. Chọn mục "Settings", thay đổi "Application Status" thành __Live__ và ấn nút "Update".
    <div class="soclall-br"></div>
    ![Linkedin : Settings Page](/img/linkedin-4-settings-page.jpg)
    <div class="soclall-br"></div>
9. Tại trang "Authentication" , bạn có thể thấy "Client ID" và "Client Secret" và lấy chúng để nhập vào Thiết lập ứng dụng LinkedIn trên SoclAll.