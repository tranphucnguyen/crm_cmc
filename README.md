# Yêu cầu
[.Net6](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)

# Hướng dẫn
1. Debug dự án
2. vào http://localhost:5102/index.html

# Thay đổi

1. Sử dụng thêm file tĩnh từ phía client vào server
   ```csharp
   app.UseStaticFiles();
   ```
1. Thêm thư mục `wwwroot` vào dự án
