<h1 align="center" style="font-weight: bold;">🐾 PetShop - Thế giới dành cho thú cưng 🐶🐱</h1>

<p align="center">
  <a href="#about">Giới thiệu</a> |
  <a href="#getting-started">Bắt đầu</a> |
  <a href="#team">Thành viên</a> |
  <a href="#contribute">Đóng góp</a> |
  <a href="#references">Tài liệu tham khảo</a>
</p>

---

<h2 id="about">✨ Giới thiệu dự án</h2>
<p>Dự án <b>PetShop</b> là nền tảng thương mại điện tử chuyên biệt cho các "boss" và "sen" yêu thương của bạn. Tại đây, bạn có thể tìm kiếm và mua sắm dễ dàng các sản phẩm dành cho thú cưng.</p>

<h3>Các công nghệ sử dụng:</h3>
<ul>
  <li>🌟 <b>Frontend</b>: HTML, CSS, Bootstrap</li>
  <li>🔧 <b>Backend</b>: Java, JavaScript, AngularJS</li>
  <li>🛠 <b>Công cụ phát triển</b>: IntelliJ IDEA/Spring Boot Suite 4</li>
</ul>
<p><b>Mục tiêu:</b> Cung cấp trải nghiệm mua sắm trực quan, tiện lợi cho người dùng.</p>

---

<h2 id="getting-started">🚀 Bắt đầu</h2>
<p>Để chạy được dự án này, hãy làm theo các bước sau:</p>

<h3>Các công cụ cần thiết</h3>
<ul>
  <li>🔗 <a href="https://git-scm.com/">Git</a>: Quản lý mã nguồn</li>
  <li>💻 <a href="https://www.jetbrains.com/idea/">IntelliJ IDEA</a>: IDE chính</li>
  <li>⚙️ <a href="https://spring.io/tools">Spring Boot Suite 4</a>: Công cụ hỗ trợ phát triển Spring</li>
  <li>📂 <a href="https://www.microsoft.com/en-us/sql-server">SQL Server</a>: Lưu trữ cơ sở dữ liệu</li>
</ul>

<h3>Clone dự án</h3>
<p>Clone repository về máy của bạn:</p>
<pre>
<code>git clone https://github.com/PhamNhatHoang/DATN_PetShop</code>
</pre>

<h3>🔧 Cấu hình biến môi trường:</h3> <p>Sao chép tệp <code>.env.example</code> thành <code>.env</code> và cập nhật thông tin cần thiết:</p>
<pre>
<code>
APP_NAME=PetShop

# Cấu hình email
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=ninjaspetshop@gmail.com
MAIL_PASSWORD="gssb rfsw ggfp mkel"
MAIL_SMTP_AUTH=true
MAIL_SMTP_STARTTLS_ENABLE=true

# Cấu hình cơ sở dữ liệu
DB_URL=jdbc:sqlserver://localhost:1433;database=PetShop;encrypt=true;trustServerCertificate=true;
DB_USERNAME=sa
DB_PASSWORD=123456
DB_DRIVER=com.microsoft.sqlserver.jdbc.SQLServerDriver
JPA_NAMING_STRATEGY=org.hibernate.boot.model.naming.PhysicalNamingStrategyStandardImpl

# Cấu hình giới hạn tải lên
MAX_FILE_SIZE=10
MAX_REQUEST_SIZE=10

# OAuth 2.0 Google
GOOGLE_CLIENT_ID=522493457603-gj4oasdonv877qm4gpqpp4l9509nbhbm.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=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

# OAuth 2.0 Facebook
FACEBOOK_CLIENT_ID=1060394182294463
FACEBOOK_CLIENT_SECRET=c5550d7dba5b6c09180ab26face76089
</code>
</pre>

---

<h2 id="team">🤝 Thành viên</h2>
<p>Đội ngũ thực hiện dự án:</p>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/member1">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Member 1"/>
        <br><sub><b>Phạm Nhật Hoàng</b></sub>
      </a>
      <p>Vai trò: Project Manager</p>
      <p>Email: hoangpnps30696@fpt.edu.vn</p>
    </td>
    <td align="center">
      <a href="https://github.com/member2">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Member 2"/>
        <br><sub><b>Ngô Việt Anh</b></sub>
      </a>
      <p>Vai trò: Backend Developer</p>
      <p>Email: anhnvps30934@fpt.edu.vn</p>
    </td>
    <td align="center">
      <a href="https://github.com/member3">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Member 3"/>
        <br><sub><b>Lê Hoàng Hiền</b></sub>
      </a>
      <p>Vai trò: Frontend Developer</p>
      <p>Email: hienlhps31008@fpt.edu.vn</p>
    </td>
    <td align="center">
      <a href="https://github.com/member4">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Member 4"/>
        <br><sub><b>Nguyễn Trọng Phúc</b></sub>
      </a>
      <p>Vai trò: Backend Developer</p>
      <p>Email: phucntps30804@fpt.edu.vn</p>
    </td>
    <td align="center">
      <a href="https://github.com/member5">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Member 5"/>
        <br><sub><b>Đỗ Minh Tâm</b></sub>
      </a>
      <p>Vai trò: Backend Developer</p>
      <p>Email: tamdmps36365@fpt.edu.vn</p>
    </td>
  </tr>
</table>

---

<h2 id="contribute">📫 Đóng góp</h2>
<p>Hướng dẫn để đóng góp:</p>
<ol>
  <li>Clone repository: <code>git clone https://github.com/PhamNhatHoang/DATN_PetShop</code></li>
  <li>Tạo nhánh mới: <code>git checkout -b feature/YOUR_BRANCH</code></li>
  <li>Commit thay đổi.</li>
  <li>Mở Pull Request và chờ phê duyệt.</li>
</ol>

---

<h3 id="references">📖 Tài liệu tham khảo</h3>
<ul>
  <li><a href="https://www.atlassian.com/git/tutorials/making-a-pull-request">📝 Cách tạo Pull Request</a></li>
  <li><a href="https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716">💾 Mẫu Commit</a></li>
</ul>
