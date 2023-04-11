FROM node:latest

# Thiết lập thư mục làm việc trong container
WORKDIR /app

# Sao chép tệp package.json và package-lock.json vào container
COPY package*.json ./

# Sao chép các tệp trong thư mục gốc vào container
COPY . .

# Mở cổng 3000 để ứng dụng có thể được truy cập từ bên ngoài
EXPOSE 3000

# Khởi động ứng dụng khi container được chạy
CMD ["npx", "lite-server"]
