<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-info">
      <a class="navbar-brand" href="Lab3Index.html">
        <img src="../components/images/logo-energy-pilates.png" alt="Logo" style="width: 150px;">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapsibleNavbar">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: black;">
              <i class="fa-solid fa-house"></i> Trang chủ
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Lab3ChuyenMuc.html" style="color: black;">
              <i class="fa-solid fa-list"></i> Bài viết
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#" style="color: black;">
              <i class="fa-solid fa-circle-info"></i> Giới thiệu
            </a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" style="color: black;">
              <i class="fa-solid fa-user"></i> Tài khoản
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Profile</a></li>
              <li><a class="dropdown-item" href="#">Đăng ký thành viên</a></li>
            </ul>
          </li>
        </ul>
        <ul class="navbar-nav d-flex">
          <li class="nav-item">
            <a class="nav-link" style="color: black;">Đăng Nhập</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" style="color: black;">Đăng Kí</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="container">
        <h1>Form Đăng Kí Thông Tin</h1>
                <form class="border p-3 rounded">
                    <div class="mb-3">
                        <label class="form-label">Họ và Tên</label>
                        <input type="text" class="form-control" placeholder="Họ và Tên">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Email</label>
                        <input type="email" class="form-control" placeholder="Nhập Email">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Số Điện Thoại</label>
                        <input type="tel" class="form-control" placeholder="Nhập Số Điện Thoại">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Mật Khẩu</label>
                        <input type="password" class="form-control" placeholder="Nhập Mật Khẩu">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Xác Nhận Mật Khẩu</label>
                        <input type="password" class="form-control" placeholder="Xác Nhận Mật Khẩu">
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Giới Tính</label>
                        <div class="d-inline-flex align-items-center ms-2">
                            <div class="form-check me-3">
                                <input type="radio" class="form-check-input" name="gender" id="male">
                                <label class="form-check-label" for="male">Nam</label>
                            </div>
                            <div class="form-check">
                                <input type="radio" class="form-check-input" name="gender" id="female">
                                <label class="form-check-label" for="female">Nữ</label>
                            </div>
                        </div>
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Ngôn Ngữ</label>
                        <select class="form-select">
                            <option>Tiếng Việt</option>
                            <option>Tiếng Anh</option>
                            <option>Tiếng Trung</option>
                        </select>
                    </div>
                    <div class="mb-3">
                        <input class="form-check-input" type="checkbox" id="myCheck" required>
                        <label class="form-check-label" for="myCheck">Tôi đồng ý với các điều khoản và điều kiện</label>
                    </div>
                    <div class="mb-3">
                        <button type="submit" class="btn btn-primary">Đăng Ký</button>
                    </div>
                    <p>If you have account <a href="Login.vue">Click here</a></p>
                </form>  
    </div>
    <footer class=" bg-dark p-3" style="color: white; text-align: center;">@copy right by FPT</footer>  
</template>