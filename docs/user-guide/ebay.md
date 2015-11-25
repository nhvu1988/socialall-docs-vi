__Để tạo một ứng dụng trên Ebay, hãy làm theo các bước sau:__

1. Đăng kí hoặc đăng nhập vào [Ebay Developers](https://developer.ebay.com/join/). Nếu bạn chưa có tài khoản trên Ebay Developers, bạn cần điền những thông tin như hình dưới để tạo tài khoản:
    <div class="soclall-br"></div>
    ![Ebay : Create account](/img/ebay-1-join-form.png)
    <div class="soclall-br"></div>
2. Sau khi tạo tài khoản thành công, bạn sẽ nhận được một email từ Ebay Developer để kích hoạt tài khoản. Sau khi tài khoản đã được kích hoạt, nhấp vào "My Account" trong danh mục đỏ trên cùng của trang.
3. Trong trang "My Account", bạn nhấn nút "Generate Production Keys". Và bạn sẽ nhìn thấy kết quả như sau:
    <div class="soclall-br"></div>
    ![Ebay : Production Keys](/img/ebay-2-production-keys.png)
    <div class="soclall-br"></div>
4. Sau đó, bạn chọn "application settings" tab. Trong trang "Manage Application Settings", bạn chọn những lựa chọn như sau:
    * Select an environment: chọn __Production__
    * Select a key set: chọn một Key Set (Tên của Key Set mà bạn vừa tạo)
    
    ![Ebay : Application Settings](/img/ebay-3-application-settings.png)
    <div class="soclall-br"></div>

5. Trong mục "Customize the eBay User Consent Form", bạn nhấp vào "Customize the eBay User Consent Form".
6. Trong mục "Application Level Settings", bạn điền những thông tin như sau:
    * Show Application Details: chọn __enabled__
    * Application URL: __https://api2.socialall.io/__
    
    ![Ebay : Application Level Settings](/img/ebay-4-application-level-settings.png)
    <div class="soclall-br"></div>
    
7. Xong, nhấn nút "Save Settings". Sau đó, trong mục "Manage Your RuNames", bạn nhấn nút "Generate Runame" button. Đợi khoảng 1 phút hoặc hơn, bạn sẽ thấy một thông báo thành công và một "RuName" vừa tạo trong mục "Manage Your RuNames".
8. Sau đó nữa, bạn tiếp tục nhấp vào "Show Details" của "RuName" vừa tạo và điền những thông tin như sau: 
    * Authorization Type: chọn __Authorization__
    * Accept Redirect URL: __https://api2.socialall.io/callback__
    * Reject Redirect URL: __https://api2.socialall.io/callback__
    
    ![Ebay : Application Settings](/img/ebay-5-manage-runame.png)
    <div class="soclall-br"></div>
    
9. Xong, nhấn nút "Save Settings" lần nữa.
10. Tại trang SocialAll, bạn chọn tab "Networks" ---> chọn "Ebay" ---> bạn chép "DevID", "AppID", "CertID", "RuName" và điền vào như hình bên dưới:
    
11. Sau cùng, bạn nhấn nút "Save".