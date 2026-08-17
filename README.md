# 23700751_HuynhNhatTruong_CABSYSTEM
| STT | Yếu điểm                                             | Phân tích                                                                                                                                                        |
| --- | ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Phân công tài xế chủ yếu thủ công**                | Việc tìm và phân công tài xế chưa được tự động hóa, gây mất thời gian và khó xử lý khi số lượng chuyến tăng.                                                     |
| 2   | **Khách hàng khó theo dõi chuyến đi**                | Khách hàng chưa dễ dàng biết hệ thống đang tìm tài xế, tài xế nào đã nhận chuyến hoặc trạng thái hiện tại của chuyến đi.                                         |
| 3   | **Thông tin thanh toán chưa được quản lý tập trung** | Việc quản lý và tra cứu thông tin thanh toán còn hạn chế.                                                                                                        |
| 4   | **Khó mở rộng hệ thống**                             | Hệ thống hiện tại gặp khó khăn khi doanh nghiệp muốn phục vụ số lượng lớn khách hàng và tài xế.                                                                  |
| 5   | **Quản lý tài xế chưa hiệu quả**                     | Chưa có cơ chế đầy đủ để quản lý trạng thái hoạt động, thông tin phương tiện và vị trí tài xế.                                                                   |
| 6   | **Khó xử lý khi tài xế từ chối hoặc không phản hồi** | Việc tìm tài xế thay thế cần được cải thiện để khách hàng không phải tạo lại yêu cầu.                                                                            |
| 7   | **Hỗ trợ thanh toán còn hạn chế**                    | Doanh nghiệp cần tích hợp với nhà cung cấp thanh toán bên ngoài và xử lý trường hợp giao dịch thất bại.                                                          |
| 8   | **Hệ thống thông báo chưa đáp ứng đầy đủ**           | Cần thông báo cho khách hàng và tài xế ở nhiều trạng thái khác nhau của chuyến đi.                                                                               |
| 9   | **Khó khăn trong công tác vận hành**                 | Nhân viên vận hành cần một giao diện quản trị để quản lý khách hàng, tài xế, phương tiện và chuyến đi.                                                           |
| 10  | **Khả năng mở rộng và thay đổi còn hạn chế**         | Doanh nghiệp muốn bổ sung dịch vụ, phương thức thanh toán, nhà cung cấp thông báo hoặc thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống. |

Tại sao cần hệ thống mới?

Do những hạn chế trên, doanh nghiệp cần xây dựng một CAB System mới nhằm:

Tự động hóa quy trình tìm và phân công tài xế dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành.

Cho phép khách hàng theo dõi chuyến đi từ lúc tạo yêu cầu cho đến khi hoàn thành.

Quản lý thông tin khách hàng, tài xế, phương tiện và chuyến đi một cách tập trung.

Hỗ trợ tính cước và thanh toán, bao gồm cả tiền mặt và thanh toán điện tử.

Xử lý trường hợp tài xế không phản hồi hoặc từ chối chuyến bằng cách tiếp tục tìm tài xế khác.

Cung cấp hệ thống thông báo cho khách hàng và tài xế trong các trạng thái quan trọng.

Hỗ trợ nhân viên vận hành theo dõi chuyến đang diễn ra, trạng thái tài xế, sự cố và lịch sử giao dịch.

Cung cấp báo cáo cho ban lãnh đạo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế.

Đảm bảo bảo mật và phân quyền đối với dữ liệu cá nhân, dữ liệu vị trí, dữ liệu giao dịch và các thao tác quản trị.

Có khả năng mở rộng độc lập, hạn chế việc một lỗi ở thanh toán hoặc thông báo làm ảnh hưởng toàn bộ hệ thống.

Dễ dàng phát triển trong tương lai, chẳng hạn như thêm loại dịch vụ, phương thức thanh toán hoặc nhà cung cấp thông báo.


B2. Xác định Stakeholder
| STT | Stakeholder                           | Vai trò / Mối quan tâm                                                                                  |
| --- | ------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| 1   | **Khách hàng**                        | Đăng ký, đặt xe, theo dõi chuyến đi, xem lịch sử, thanh toán và đánh giá tài xế.                        |
| 2   | **Tài xế**                            | Quản lý hồ sơ, phương tiện, trạng thái hoạt động, nhận/từ chối chuyến và cập nhật trạng thái chuyến đi. |
| 3   | **Nhân viên vận hành**                | Quản lý khách hàng, tài xế, phương tiện, chuyến đi và hỗ trợ xử lý các trường hợp lỗi.                  |
| 4   | **Ban giám đốc**                      | Định hướng hệ thống và theo dõi các báo cáo về chuyến đi, doanh thu và hiệu quả hoạt động.              |
| 5   | **Nhà cung cấp thanh toán bên ngoài** | Cung cấp dịch vụ xử lý thanh toán điện tử cho hệ thống CAB.                                             |
| 6   | **Nhà cung cấp dịch vụ thông báo**    | Hỗ trợ gửi thông báo đến khách hàng và tài xế.                                                          |
| 7   | **Business Analyst (BA)**             | Làm rõ các yêu cầu chưa được xác định và xác nhận yêu cầu với các bên liên quan trước khi phát triển.   |
| 8   | **Nhóm phát triển hệ thống**          | Xây dựng hệ thống dựa trên các yêu cầu đã được phân tích và xác nhận.                                   |

Stakeholder Matrix
|                | **Interest thấp**                                                                                               | **Interest cao**                                                                                                                                             |
| -------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Power cao**  | **Nhà cung cấp thanh toán**  <br>Ảnh hưởng đến hoạt động thanh toán nhưng không sử dụng hệ thống CAB hằng ngày. | **Ban giám đốc**  <br>Đưa ra định hướng và kỳ vọng đối với hệ thống. <br><br> **Nhân viên vận hành**  <br>Trực tiếp quản lý và xử lý hoạt động của hệ thống. |
| **Power thấp** | **Nhóm phát triển hệ thống**  <br>Thực hiện việc xây dựng hệ thống theo yêu cầu đã được xác định.               | **Khách hàng**  <br>Người sử dụng trực tiếp dịch vụ đặt xe. <br><br> **Tài xế**  <br>Người sử dụng trực tiếp hệ thống để nhận và thực hiện chuyến.           |
                         INTEREST
                    THẤP              CAO
                 ┌──────────────┬────────────────────┐
      CAO        │ Nhà cung cấp │ BAN GIÁM ĐỐC       │
                 │ thanh toán   │ NHÂN VIÊN VẬN HÀNH │
     POWER       ├──────────────┼────────────────────┤
      THẤP       │ Nhóm phát    │ KHÁCH HÀNG         │
                 │ triển        │ TÀI XẾ              │
                 └──────────────┴────────────────────┘
              

