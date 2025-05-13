# My Java Project

Энэхүү төслийг Java хэл дээр бүтээсэн бөгөөд Maven ашиглан бүтээц, тест болон кодын чанар шалгалтыг хийдэг. Төсөл нь дараах Maven залгаасуудыг (plugin) ашигладаг:

- **JUnit 5 (junit-jupiter)** - Нэгж тест хийхэд
- **Maven Surefire Plugin** - Тестийг ажиллуулах
- **Maven Checkstyle Plugin** - Кодын стандарт (Google style) шалгах
- **JaCoCo Maven Plugin** - Тестийн кодын хамрах хүрээг хэмжих

## ⚙️ Тохиргоо

Төслийг ажиллуулахын өмнө дараах зүйлийг шалгаарай:

- Java 17 болон түүнээс дээш хувилбар
- Maven 3.x

## 🏗️ Төсөл бүтээх

```bash
mvn clean install
