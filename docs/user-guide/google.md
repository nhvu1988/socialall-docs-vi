__Để đăng kí 1 ứng dụng trên Google, vui lòng làm theo các bước sau:__

1. Đăng nhập vào [Google Account](https://accounts.google.com/) và đi đến trang [Google Developer](https://console.developers.google.com/) để tạo ứng dụng
2. Nhấn nút "Create Project" và điền tên project và id project
    <div class="soclall-br"></div>
    ![Google : Create Form](/img/google-2-create-form.JPG)
    <div class="soclall-br"></div>
3. Khi project được tạo thành công, chọn mục "Consent screen" và điền "Product Name" sau đó ấn nút "Save".
    <div class="soclall-br"></div>
    ![Google : Consent Screen](/img/google-3-consent-screen.jpg)
    <div class="soclall-br"></div>
4. Sau đó, chọn mục "Credentials", nhấn nút "Create new Client ID" và điền thông tin bên dưới
    * Application Type: chọn __Web application__
    * Authorized Javascript Origins: __http://api.soclall.com/__
    * Authorized Redirect Uris: __https://api.soclall.com/callback__
5. Sau đó nhấn nút "Create Client ID"
    <div class="soclall-br"></div>
    ![Google : Credentials](/img/google-4-credentials.JPG)
    <div class="soclall-br"></div>
6. Chọn mục "APIs", tại "API Library", chọn "Google+ API" trong mục "Social APIs".
7. Sau đó nhấn nút "Enable API".
    <div class="soclall-br"></div>
    ![Google : Enable APIs](/img/google-5-apis.jpg)
    <div class="soclall-br"></div>
8. Sau khi tạo thành công Client Id, bạn có thể lấy "Client ID" và "Client Secret" để điền vào SoclAll Google Settings form.
    <div class="soclall-br"></div>
    ![Google : Client Info](/img/google-5-client-info.JPG)
    <div class="soclall-br"></div>