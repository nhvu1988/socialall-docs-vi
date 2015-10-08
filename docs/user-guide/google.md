__Để đăng kí một ứng dụng trên Google, vui lòng làm theo các bước sau:__

1. Đăng nhập vào [Google Account](https://accounts.google.com/) và đi đến trang [Google Developer](https://console.developers.google.com/) để tạo ứng dụng
2. Nhấn nút "Create Project" và điền tên ứng dụng (Project name). Sau khi điền xong, nhấn nút "Create".
    <div class="soclall-br"></div>
    ![Google : Create Form](/img/google-2-create-form.JPG)
    <div class="soclall-br"></div>
3. Sau khi ứng dụng được tạo thành công, chọn mục "Credentials" và chọn tab "OAuth consent screen", điền những thông tin cơ bản. Sau khi điền xong, nhấn nút "Save".
    <div class="soclall-br"></div>
    ![Google : Consent Screen](/img/google-3-consent-screen.jpg)
    <div class="soclall-br"></div>
4. Sau đó, chọn tab "Credentials", nhấn nút "Add credentials" và chọn "OAuth 2.0 client ID". Tiếp theo đó, chọn "Web application" và điền thông tin bên dưới:
    * Authorized Javascript Origins: __http://api2.socialall.io/__
    * Authorized Redirect Uris: 
        - __http://api2.socialall.io/callback__
        - __https://api2.socialall.io/callback__
5. Sau đó nhấn nút "Create"
    <div class="soclall-br"></div>
    ![Google : Credentials](/img/google-4-credentials.JPG)
    <div class="soclall-br"></div>
6. Chọn mục "APIs", tại "API Library", chọn "Google+ API" trong mục "Social APIs".
7. Sau đó nhấn nút "Enable API".
    <div class="soclall-br"></div>
    ![Google : Enable APIs](/img/google-5-apis.jpg)
    <div class="soclall-br"></div>
8. Sau khi tạo thành công Client Id, tại trang "Credentials", nhấn chọn client ID vừa tạo, bạn có thể thấy "Client ID", "Client Secret" và lấy chúng để nhập vào Thiết lập ứng dụng Google trên SocialAll.
    <div class="soclall-br"></div>
    ![Google : Client Info](/img/google-6-client-info.JPG)
    <div class="soclall-br"></div>