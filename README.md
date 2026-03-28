# NNM28-03class

## Import user tu file Excel

- Endpoint: `POST /api/v1/users/import`
- Form-data: `file`
- Sheet dau tien can co it nhat 2 cot `username` va `email`
- Role duoc gan co dinh la `USER/user` (tim theo ten role, khong phan biet hoa thuong)
- Moi user duoc tao voi password ngau nhien 16 ky tu va gui qua Mailtrap

## Cau hinh Mailtrap

Dat bien moi truong truoc khi chay:

- `MAILTRAP_HOST=sandbox.smtp.mailtrap.io`
- `MAILTRAP_PORT=2525`
- `MAILTRAP_USER=your_mailtrap_user`
- `MAILTRAP_PASS=your_mailtrap_pass`
- `MAIL_FROM=admin@haha.com`

## Ket qua tra ve

API se tra ve:

- So dong thanh cong/that bai
- Ket qua chi tiet tung dong import
- Ten role da gan cho user
