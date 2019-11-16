# 1. Cppcheck
Một số thông báo lỗi trả về sau khi sử dụng Cppcheck:

<img src="check1.png">

<img src="check2.png">

<img src="check3.png">

<img src="check4.png">

<img src="check5.png">


Cppcheck hỗ trợ nhiều loại kiểm tra tĩnh có thể không được trình biên dịch bao phủ. Các kiểm tra này là kiểm tra phân tích tĩnh có thể được thực hiện ở cấp mã nguồn. Chương trình này hướng tới kiểm tra phân tích tĩnh nghiêm ngặt, thay vì tiếp cận bằng cảm tính, mang tính kinh nghiệm.

Một số kiểm tra được hỗ trợ bao gồm:

    - Kiểm tra biến tự động
    - Giới hạn kiểm tra các lỗi tràn mảng
    - Kiểm tra các lớp (ví dụ: các hàm không được sử dụng, khởi tạo biến và sao chép bộ nhớ)
    - Việc sử dụng các hàm không dùng hoặc thay thế
    - Kiểm tra an toàn ngoại lệ, ví dụ sử dụng phân bổ bộ nhớ và kiểm tra hàm hủy
    - Rò rỉ bộ nhớ, ví dụ: do phạm vi bị mất mà không có sự phân bổ
    - Rò rỉ tài nguyên, ví dụ do quên đóng một tập tin xử lý
    - Việc sử dụng không hợp lệ các chức năng và thành ngữ của Thư viện mẫu tiêu chuẩn
    - Lỗi phong cách và hiệu suất linh tinh

Cũng như nhiều chương trình phân tích, có nhiều trường hợp bất thường về thành ngữ lập trình có thể được chấp nhận trong các trường hợp đích cụ thể hoặc nằm ngoài phạm vi của lập trình viên để sửa mã nguồn.

# 2. CodeScene

[![](https://codescene.io/projects/5870/status.svg) Get more details at **codescene.io**.](https://codescene.io/projects/5870/jobs/16598/results)

- CodeScene ưu tiên các vấn đề về "nợ kỹ thuật" và chất lượng code dựa trên cách tổ chức làm việc thực sự với code. Do đó, CodeScene giới hạn kết quả trả về với các thông tin được kiểm tra.

-CodeScene cũng vượt xa các công cụ truyền thống bằng cách đo lường việc tổ chức trong hệ thống để phát hiện các tắc nghẽn phối hợp trong kiến trúc phần mềm, rủi ro  và lỗ hổng kiến thức.
- CodeScene liên kết với github rất tiện cho việc lấy mã nguồn và đây là công cụ kiểm thử tĩnh cho nhiều ngôn ngữ khác nhau.
