<h1 align="center" style="font-weight: bold;">JavaNinjas💻</h1>

<p align="center">
  <a href="#technologies">Công nghệ sử dụng</a> |
  <a href="#getting-started">Bắt đầu</a> |
  <a href="#api-endpoints">API Endpoints</a> |
  <a href="#team">Thành viên</a> |
  <a href="#contribute">Đóng góp</a>
</p>

<p align="center">Dự án <b>JavaNinjas</b> chuyên về trang bán đồ cho Làng Lá.</p>

<p align="center">
  <a href="https://github.com/PhamNhatHoang/DATN_Fpoly">📱 Tham khảo dự án</a>
</p>

<h2 id="technologies">💻 Công nghệ sử dụng</h2>
<ul>
  <li>AngularJS</li>
  <li>Thymeleaf</li>
  <li>Spring Boot</li>
  <li>API Payment</li>
</ul>

<h2 id="getting-started">🚀 Bắt đầu</h2>
<p>Để chạy được dự án này, bạn cần thực hiện các bước sau:</p>

<h3>Yêu cầu</h3>
<ul>
  <li><a href="https://nodejs.org/">NodeJS</a></li>
  <li><a href="https://git-scm.com/">Git 2</a></li>
</ul>

<h3>Clone dự án</h3>
<p>Cách để clone dự án về máy:</p>

```bash
git clone https://github.com/PhamNhatHoang/DATN_Fpoly.git
```

<h3>Cấu hình biến môi trường</h3>
<p>Sử dụng tệp <code>.env.example</code> để tạo tệp cấu hình <code>.env</code> của bạn với thông tin AWS Credentials.</p>

```yaml
NODE_AWS_REGION=us-east-1
NODE_AWS_KEY_ID={YOUR_AWS_KEY_ID}
NODE_AWS_SECRET={YOUR_AWS_SECRET}
```

<h3>Chạy dự án</h3>
<p>Hướng dẫn để bắt đầu dự án:</p>

```bash
cd project-name
npm install
npm start
```

<h2 id="api-endpoints">📍 API Endpoints</h2>
<p>Danh sách các API chính và yêu cầu dữ liệu tương ứng:</p>

<table>
  <thead>
    <tr>
      <th>Đường dẫn</th>
      <th>Mô tả</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><kbd>GET /authenticate</kbd></td>
      <td>Nhận thông tin người dùng. Xem chi tiết <a href="#get-auth">tại đây</a>.</td>
    </tr>
    <tr>
      <td><kbd>POST /authenticate</kbd></td>
      <td>Xác thực người dùng. Xem chi tiết <a href="#post-auth">tại đây</a>.</td>
    </tr>
  </tbody>
</table>

<h3 id="get-auth">GET /authenticate</h3>
<p><b>Kết quả:</b></p>

```json
{
  "name": "Fernanda Kipper",
  "age": 20,
  "email": "her-email@gmail.com"
}
```

<h3 id="post-auth">POST /authenticate</h3>
<p><b>Yêu cầu:</b></p>

```json
{
  "username": "fernandakipper",
  "password": "4444444"
}
```

<p><b>Kết quả:</b></p>

```json
{
  "token": "OwoMRHsaQwyAgVoc3OXmL1JhMVUYXGGBbCTK0GBgiYitwQwjf0gVoBmkbuyy0pSi"
}
```

<h2 id="team">🤝 Thành viên</h2>
<p>Cảm ơn các thành viên đã tham gia dự án tốt nghiệp. Chúc các bạn thành công trên con đường đã chọn:</p>

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/PhamNhatHoang">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Phạm Nhật Hoàng Profile Picture"/>
        <br><sub><b>Phạm Nhật Hoàng</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ShaanCoding">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Đỗ Minh Tâm Profile Picture"/>
        <br><sub><b>Đỗ Minh Tâm</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/tamXinchao">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Lê Hoàng Hiền Profile Picture"/>
        <br><sub><b>Lê Hoàng Hiền</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Chanh03">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Ngô Việt Anh Profile Picture"/>
        <br><sub><b>Ngô Việt Anh</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/PhamNhatHoang">
        <img src="https://thanhcongfarm.com/wp-content/uploads/2022/05/anh-cho-hai-20.jpg" width="100px;" alt="Nguyễn Trọng Phúc Profile Picture"/>
        <br><sub><b>Nguyễn Trọng Phúc</b></sub>
      </a>
    </td>
  </tr>
</table>

<h2 id="contribute">📫 Đóng góp</h2>
<p>Hướng dẫn để các developer khác có thể đóng góp vào dự án:</p>

<ol>
  <li>Clone repository: <code>git clone https://github.com/PhamNhatHoang/DATN_Fpoly.git</code></li>
  <li>Tạo nhánh mới: <code>git checkout -b feature/YOUR_BRANCH</code></li>
  <li>Commit thay đổi của bạn.</li>
  <li>Mở Pull Request và chờ phê duyệt.</li>
</ol>

<h3>Tài liệu tham khảo</h3>
<ul>
  <li><a href="https://www.atlassian.com/git/tutorials/making-a-pull-request">📝 Cách tạo Pull Request</a></li>
  <li><a href="https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716">💾 Mẫu Commit</a></li>
</ul>
