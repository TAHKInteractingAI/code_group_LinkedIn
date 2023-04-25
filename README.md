# Tool linkedin
Download project về máy

```bash
git clone https://github.com/botsamqntdata/tool_linkedin.git
```
## Thiết lập môi trường để chạy tool
Mở cmd trong project và tạo môi trường ảo trong folder vừa tải, trước đó phải cài python trên máy
``` bash
python -m venv venv
```
Kích hoạt môi trường ảo
``` bash
venv\Scripts\activate.bat
```
Cài đặt các thư viện cần thiết
```bash
pip install -r requirements.txt
```
Thay đổi thông tin trong file Account.cfg
```python
[API_KEYS]
hunter = API KEYS hunter

[CREDS]
linkedin_username = 
linkedin_password = 
```

## Chạy tool auto join group bằng câu lệnh
```bash
python LinkedIn_group_tool_Feature123.py
```
## Chạy tool auto post group bằng câu lệnh
```bash
python Auto_post_group.py
```
