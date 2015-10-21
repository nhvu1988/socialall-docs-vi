__Để đăng kí một ứng dụng trên Live, vui lòng làm theo các bước sau:__

1. Đăng nhập vào[Microsoft account](https://account.live.com/) và đi đến trang [Microsoft Developer](https://account.live.com/developers/applications) để tạo ứng dụng
2. Nhấn nút "Create application", sau đó điền Tên ứng dụng và chọn đồng ý ô "Term Of Service".
3. Đi đến phần "Api Settings" và điền theo thông tin bên dưới:
    * Redirect URLs: __http://api2.socialall.io/callback__
    * Sau đó, chọn "Add another redirect URL" và điền tiếp: __https://api2.socialall.io/callback__
    
    <div class="soclall-br"></div>
    ![Live : Api Settings Form](/img/live-1-api-settings-form.JPG)
    <div class="soclall-br"></div>
    
4. Sau khi đã điền xong, nhấn nút "Save".
5. Đi đến trang "App Settings", bạn có thể thấy "Client ID" và "Client secret".
    <div class="soclall-br"></div>
    ![Live : Api Settings Form](/img/live-2-app-settings-form.JPG)
    <div class="soclall-br"></div>
6. Tại trang SocialAll, bạn chọn tab "Networks" ---> chọn "Live" ---> bạn chép "Client ID", "Client secret" và điền vào như hình bên dưới:
    <div class="soclall-br"></div>
    ![Live : Config Api](/img/live-3-config-api.jpg)
    <div class="soclall-br"></div>
7. Sau cùng, bạn nhấn nút "Save".