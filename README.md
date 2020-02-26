# NotificationDUT


![Image description](https://github.com/tranvanduong2483/NotificationDUT/blob/master/image/1.png?s=50)
![Image description](https://github.com/tranvanduong2483/NotificationDUT/blob/master/image/2.png?s=100)
![Image description](https://github.com/tranvanduong2483/NotificationDUT/blob/master/image/3.png?s=100)
![Image description](https://github.com/tranvanduong2483/NotificationDUT/blob/master/image/4.png?s=50)



1. Lý do chọn đề tài:

    HỆ THỐNG THÔNG TIN SINH VIÊN - TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG”

    Hiện tại có 3 vấn đề đang gặp phải:
    - Vấn đề về “Thông báo chung”: sự bất tiện của hệ thống này khi buộc sinh viên phải chủ động kiểm tra thông báo trên trang sv.dut.udn.vn. Đặc biệt vào mùa hè khi mà sinh viên vẫn đang nghỉ giải lao thì trường lại thông báo làm một số việc, khiến sinh viên bỏ lỡ.
    - Vấn đề về “TB lớp học phần”: Khi một giảng viên dạy bù hoặc nghỉ một buổi của học phần nào đó. Sẽ có thông báo trên trang đào tạo nhưng sinh viên chỉ chủ động liên tục kiểm tra ở trang web mới có thể biết được thông báo đó. Khắc phục nhược điểm trên giảng viên thường gửi mail đến lớp trưởng của lớp học đó. Nhưng đối với những sinh viên học trái lớp, học ghép, học vượt, … thì lại bị bỏ lỡ thông báo.
        https://docs.google.com/document/d/1p4vTYZkI5ojfrxBh6Vz8rYC01VmAdTWyBeTRr4UdnSs/edit
    - Vấn đề Xem lịch học mỗi khi trang web trường bị lỗi: sinh viên không thể xem lịch học

    "Yêu cầu bài toán đặt ra: Khi trường thông báo một số công việc, thầy cô thông báo nghỉ học hoặc học bù, sinh viên không bỏ lỡ, xem lịch offline"

2. Mô tả bài toán: Xây dựng ứng dụng Android thông báo từ việc lấy dữ liệu từ sv.dut.udn.vn
    - Nhận "Thông báo chung"
    - Nhận "Thông báo đến lớp học phần"
    - Nhận thông báo qua email hoặc thông báo ngay trên ứng dụng
    - Xem lịch học offline

3.1 Sơ đồ hoạt động

    ![alt text](https://scontent.fhan7-1.fna.fbcdn.net/v/t1.0-9/79249965_1216056015247101_7933552869209276416_o.jpg?_nc_cat=111&_nc_ohc=amftnehnfKwAQkIHRFZ4YmrVBalAc0NHMMRQs3wRXBIG0B-1Bs0Y_5kxQ&_nc_ht=scontent.fhan7-1.fna&oh=624ff3a467ceb66167e5bfaaa86c1864&oe=5E8B1757)

3.2 Firebase Database Realtime:

    https://lh3.googleusercontent.com/BzgOX5UZYhgPKB-5mjlBKudEs2C_QH7nBFKNNyxWcYfHthppRpIsPWPXfOa6ToHLkGlTOCgBIGTxuJkurZkWwAXY7ZCXlsUb1pXvfRtQ70dTH21VU8vYywSgHa6A4HMdtRfyQKNXQnAn5ywMwZeq4D4K1XzO0Q8MvrxRJX_ysAz6ZmMyWxRV5Tb4QMxmdkU_SLh7dy4HlORo2z-Vv4bXivSzqThT53lzgGo9eHubxtK9rPp1WHmxXD05uPiWtVrCnsuBkF8HRcGAn653zDKpuCDYJ8zN4V5JN2s-6EoEd9UA9EsRZreFp4e-j1SwLJbLcodZWIl2PIa-5CSWiYn_rwFQoKYCR56k6yJNagOlqgx8PsxLqdxE491NB5-glsB5LatYbewZVW-_NQ35Z2ntxFOQd_oS3MQX2QZQd3IQSuRpdLEiXC2dGCCxd-JA0hYhZCcRSzWVwtjsF9VTEdtwyt_BXS42tdGXjHTlpktI0ts0vPWgqAaVnZ7NRgRiTPKIJMOmN_rjanR5YSNnCDVrFdz-4w0UGxU3MoRkYZUSECBDp04e5F71SC-mzEe-yGUB35Q-JliD9SeVnfRx-RFZpI6PqaHDCmbsv5bQYGGKfaGIye1LjFwqG9k1Q0_j6BkeHkavUbIBdyM0DCoI7RpEWnBTvFzC5RNEZYDsVF0FyyKcUhHnb4kgQiRm=w1814-h1780-no

4. Link phân bổ nhiệm vụ:

    https://docs.google.com/spreadsheets/d/10mbjg_QRdjWZ8HSLeU-ePyI4BCgqYgXwHZRAMk11ETQ

5. Link demo ứng dụng:

    https://www.youtube.com/watch?v=vbTvzUCPBqM

    https://youtu.be/IvCQnJ6cVoQ

6. Dự án được chia sẽ:

    Ứng dụng này là một phần của đồ án Lập trình mạng:
    Bản báo cáo: https://docs.google.com/document/d/*****/edit#heading=h.y1979wmu71wj

7. Mã nguồn: 

    Client (Android): https://github.com/tranvanduong2483/NotificationDUT

    Server (Nodejs): https://github.com/tranvanduong2483/server-dut-notification

 
