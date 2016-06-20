# Best Practice cho các nhà phát triển Android
Những bài học kinh nghiệm này được đúc kết từ các nhà phát triển [Futurice](http://futurice.com/). Các hướng dẫn này tránh tạo lại những chiếc *bánh xe*. 
# Tóm tắt
**[Hướng dẫn sử dụng Gradle và cấu trúc một project](#xây-dựng-hệ-thống)**

**[Đặt passwork và dữ liệu nhạy cảm trong gradle.properties]()**

**[Sử dụng thư viện Jackson để parse JSON data ]()**

**[Không nên dùng HTTP client, thay thế bằng Volley or OkHttp libraries]()**

**[Tránh Guava và chỉ sử dụng một vài libraries có giới hạn 65k method]()**

**[Sử dụng Fragments để Hiển thị một UI screen]()**

**[Sử dụng Activities chỉ để quản lý Fragments](#Activities-and-Fragments)**

**[Các Layout XMLs cũng là code, vậy nên tổ chức code tốt ]()**

**[Sử dụng styles để tránh trùng lặp các thuộc tính trong các layout XMLs]()**

**[Sử dụng nhiều style files tránh một file duy nhất]()**

**[Giữ cho file colors.xml ngắn gọn và xúc tích, chỉ cần định nghĩa bảng màu]()**

**[Cũng giữ cho dimens.xml xúc tích, define generic constants]()**

**[Không làm quá nhiều tầng phân cấp trong ViewGroups]()**

**[Tránh tiến trình client-side đối với WebViews, và cẩn thận không kiểm soát được tiến trình]()**

**[Dùng Robolectric cho unit tests, Robotium đối với connected (UI) tests]()**

**[Sử dụng Genymotion để tạo thiết bị ảo]()**

**[Luôn sử dụng ProGuard hoặc DexGuard]()**

**[Sử dụng SharedPreferences cho simple persistence, otherwise ContentProviders]()**

**[Sử dụng Stetho để debug app]()**

#Xây dựng hệ thống
#Activities and Fragments
