# Task-GoLang

### Câu 1: Tìm hiểu về Golang & HTTP request/response	   

        Keyword: client, server, web service.
#### Golang
  - Là một ngôn ngữ có cú phát ngắn ngọn
  - Tốc độ nhanh khi trực tiếp dịch sang mã máy
  - Có thể xử lý đa luồng một cách tối ưu (goroutines)
  - Go có thể dễ dàng maintain vì cú phát đơn giản
    
#### HTTP request/response
 HTTP là giao thức liên kết giữa client và server, client sẽ đưa ra các request và server sẽ đáp trả bằng response

    1. Client
     - Thường là thiết bị đầu cuối có vai trò gửi các request về server và nhận cái response từ server trả về
     - HTTP request sẽ bao gồm
        + HTTP Method (GET,POST,PUT,DELETE)
        + URL
        + Headers: cung cấp một số thông tin bổ sung
        + Body: chứa dữ liệu gửi lên server
    2. Server
     - Là nơi cung cấp các dịch vụ, tài nguyên và dữ liệu cho các client, server sẽ tiếp nhận các request và sẽ đáp trả bằng response
     - HTTP response sẽ bao gồm 
        + Status Line (Status Code, Status Mesage, HTTP protocol version)
        + Headers: cung cấp thông tin bổ sung
        + Body: chưa dữ liệu mà server trả về
    3. Web Service
     - Là phương thức giao tiếp giữa hai hệ thống qua mạng thường được thực hiện qua các giao thức như HTTP,HTTPS
     - Cho phép trao đổi dữ liệu và thực hiện chức năng mà không phụ thuộc vào ngôn ngữ lập trình hay công nghệ sử dụng
