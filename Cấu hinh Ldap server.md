# windows-server-2012-R2:
đầu tiên add thêm tính năng:
![image](https://user-images.githubusercontent.com/57949576/126130371-5222976e-1940-4840-99d8-4322fad73a5a.png)
chọn next next tới phần server roles:
Rồi tích vào Active Direction Lightweight Direction Services:
![image](https://user-images.githubusercontent.com/57949576/126130475-c5f113b4-f075-4460-ba81-8b043f2a88e3.png)
Sau đó next next tiếp tới cài đặt.
![image](https://user-images.githubusercontent.com/57949576/126130643-818aee47-0815-4805-b11d-cbf4f8ba79f7.png)
Sau khi cài xong 
![image](https://user-images.githubusercontent.com/57949576/126130684-95514e59-a23d-49bf-af14-776240ad2f2a.png)
Tiếp vào setup wizard 
![image](https://user-images.githubusercontent.com/57949576/126130773-18659ae6-6122-4b90-a97e-83e1622e2944.png)
Mục Instance Name và Description : điền tên tùy ý dễ liên tưởng tới.
![image](https://user-images.githubusercontent.com/57949576/126130956-48e29f9d-333b-408f-9f78-837d36780690.png)
Tiếp theo set port theo mặc định như hình 
![image](https://user-images.githubusercontent.com/57949576/126131010-12c942b7-7e1b-4b74-8350-bf68e85152cc.png)
Sang phần tiếp theo có thể chọn tạo thêm phần mới hoặc không. Nếu tạo thêm phần mới thì tham khảo hình sau:
![image](https://user-images.githubusercontent.com/57949576/126131161-2f217de5-8a4b-414a-8dba-adb5daab004c.png)
Trong đó CN, DC phải theo domain controller đã tạo.
Tiếp theo để đường dẫn mặc định và next 
![image](https://user-images.githubusercontent.com/57949576/126131237-2632b217-0e6b-4270-a0ad-8df3a3529b1d.png)
Tiếp theo chọn Network Account như hình 
![image](https://user-images.githubusercontent.com/57949576/126131363-dadd5697-935e-42b2-b763-292ed7fa81b3.png)
Sau đó confirm lại chọn Yes
![image](https://user-images.githubusercontent.com/57949576/126131406-97e01cfa-316f-4e97-891b-a6825f885d62.png)
Sang phần tiếp lựa chọn luôn phần tài khoản đang đăng nhập trên máy:
![image](https://user-images.githubusercontent.com/57949576/126131519-46949eed-c5e5-44a9-a056-4a55f5ecf874.png)
Tới import file LDAP thì ta tích hết các file. 
![image](https://user-images.githubusercontent.com/57949576/126131617-aa82bca6-e394-4e29-a0de-217507b3662f.png)
Sau đó bấm next cài đặt
![image](https://user-images.githubusercontent.com/57949576/126131690-f999daaa-ab30-465e-b840-3a46160e6522.png)
Cuối cùng finish
![image](https://user-images.githubusercontent.com/57949576/126131726-e717d965-c807-4ccb-aa39-e62ab8e31a34.png)
Tiếp theo vào TOOL --> ADSL edit để chỉnh sửa lại trong LDAP hoặc WIN+X gõ adsiedit.msc
![image](https://user-images.githubusercontent.com/57949576/126132354-b4d21fc5-40d2-4060-92eb-2abbda78035b.png)
Tiếp theo chọn tab Action--> Connect to
![image](https://user-images.githubusercontent.com/57949576/126132853-83d2c7f9-5747-49ab-a3a5-e4a3d2ab260f.png)
Điền thông tin vào như hình nếu muốn tự đặt tên và tự điền các DC=minh,DC=com là Domain controller tương ứng được cài trước đó.
Sau khi cài đặt xong sẽ được như hình
![image](https://user-images.githubusercontent.com/57949576/126133090-33afae69-c055-46f3-94c5-8ce797cf34e5.png)




