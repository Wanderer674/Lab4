<template>
  <div class="container">
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
        <div id="carousel" class="carousel slide">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="slide1">
                </button>
                <button type="button" data-bs-target="#carousel" data-bs-slide-to="1" aria-current="true" aria-label="slide2">
                </button>
                <button type="button" data-bs-target="#carousel" data-bs-slide-to="2" aria-current="true" aria-label="slide3">
                </button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../components/images/banner1.jpg" class="d-block w-100" alt="">
                </div>
                <div class="carousel-item">
                    <img src="../components/images/banner2.jpg" class="d-block w-100" alt="">
                </div>
                <div class="carousel-item">
                    <img src="../components/images/banner3.jpg" class="d-block w-100" alt="">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carousel" data-bs-slide="prev"> 
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Prev</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carousel" data-bs-slide="next"> 
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
    <h3 class="text-info">Tất Cả Bài Viết</h3>
                <div class="row">
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Phương pháp tập Pilates giúp phục hồi chấn thương cột sống 
                        <p class="fa-solid fa-message">  16</p></h5>
                        <img class="img-fluid rounded d-block" src="../components/images/tap-piltes.jpg" alt="">
                        <p>
                            Ngoài việc giúp duy trì vóc dáng, cảu thiện sự linh hoạt, dẻo dai,
                            các bài tập Piltes còn có khả năng trị đau lưng, là giải pháp hữu hiệu để phục hồi chấn thương cuộc sống
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Đây là những gì 1 giờ tập Pilates có thể làm cho cơ thể của bạn
                            <p class="fa-solid fa-message">  8</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/tap-pilates1.jpg" alt="">
                        <p>
                            Được thiết kế để xây dựng cơ bắp săn chắc, khỏe mạnh hơn, bài tập này trở thành một cái tên rất quen thuộc nhờ có rất 
                            nhiều người nổi tiếng theo dõi
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Tập Pilates có thể cải thiện sức khỏe tim mạch của bạn
                            <p class="fa-solid fa-message">  5</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/tim-mach.jpg" alt="">
                        <p>
                            Tập Pilates không chỉ giúp bạn có một cơ thể linh hoạt và khỏe mạnh mà còn có rất nhiều lợi ích cho sức khỏe tim mạch.
                            Bài viết này sẽ tìm hiểu sâu hơn về tác động tích cực của Pilates đới với sức khỏe tim mạch.
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">EAT CLEAN: Nên Và Không Nên Ăn Những Thực Phẩm nào? 
                            <p class="fa-solid fa-message">  3</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/eat-clean.png" alt="">
                        <p>
                            Chúng ta luôn chú trọng lựa chọn thực phẩm sạch và duy trì lối sống lành mạnh. Vậy chế độ eat clean nên và
                            không nên ăn gì trong thực đơn hằng ngày để cân bằng tháp dinh dưỡng cho cơ thể?
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Phương pháp tập Pilates giúp phục hồi chấn thương cột sống 
                        <p class="fa-solid fa-message">  16</p></h5>
                        <img class="img-fluid rounded d-block" src="../components/images/tap-piltes.jpg" alt="">
                        <p>
                            Ngoài việc giúp duy trì vóc dáng, cảu thiện sự linh hoạt, dẻo dai,
                            các bài tập Piltes còn có khả năng trị đau lưng, là giải pháp hữu hiệu để phục hồi chấn thương cuộc sống
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Đây là những gì 1 giờ tập Pilates có thể làm cho cơ thể của bạn
                            <p class="fa-solid fa-message">  8</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/tap-pilates1.jpg" alt="">
                        <p>
                            Được thiết kế để xây dựng cơ bắp săn chắc, khỏe mạnh hơn, bài tập này trở thành một cái tên rất quen thuộc nhờ có rất 
                            nhiều người nổi tiếng theo dõi
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">Tập Pilates có thể cải thiện sức khỏe tim mạch của bạn
                            <p class="fa-solid fa-message">  5</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/tim-mach.jpg" alt="">
                        <p>
                            Tập Pilates không chỉ giúp bạn có một cơ thể linh hoạt và khỏe mạnh mà còn có rất nhiều lợi ích cho sức khỏe tim mạch.
                            Bài viết này sẽ tìm hiểu sâu hơn về tác động tích cực của Pilates đới với sức khỏe tim mạch.
                        </p>
                    </div>
                    <div class="col-3 border rounded">
                        <h5 class="mt-3 bg-light rounded border p-3 rounded">EAT CLEAN: Nên Và Không Nên Ăn Những Thực Phẩm nào? 
                            <p class="fa-solid fa-message">  3</p></h5>
                            <img class="img-fluid rounded d-block" src="../components/images/eat-clean.png" alt="">
                        <p>
                            Chúng ta luôn chú trọng lựa chọn thực phẩm sạch và duy trì lối sống lành mạnh. Vậy chế độ eat clean nên và
                            không nên ăn gì trong thực đơn hằng ngày để cân bằng tháp dinh dưỡng cho cơ thể?
                        </p>
                    </div>
                </div>
                <ul class="pagination justify-content-center mt-4">
                    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                    <li class="page-item"><a class="page-link" href="#">1</a></li>
                    <li class="page-item"><a class="page-link" href="#">2</a></li>
                    <li class="page-item"><a class="page-link" href="#">3</a></li>
                    <li class="page-item"><a class="page-link" href="#">Next</a></li>
                    </ul>
  </div>
    <footer class=" bg-dark p-3" style="color: white; text-align: center;">@copy right by FPT</footer>  
</template>
