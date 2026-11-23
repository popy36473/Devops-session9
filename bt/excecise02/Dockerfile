# Bước 1: Chọn ảnh cơ sở
FROM eclipse-temurin:17-jre-alpine

# Bước 2: Thư mục làm việc
WORKDIR /app

# Bước 3: Copy file .jar vào container
COPY build/libs/payment-service-1.0.0.jar app.jar

# Bước 4: Mở cổng 8080
EXPOSE 8080

# Bước 5: Lệnh khởi động ứng dụng
ENTRYPOINT ["java", "-jar", "app.jar"]
