<template>
    <section id="topbox">
      <div id="topnav">
        <div class="container">
          <div class="row mx-0">
            <div class="col-12 col-sm-12 col-md-8 col-lg-2 mb-2 px-2">
              <div class="logo_page">
                <img
                  src="../assets/login_pages/LOGO.png"
                  alt="LOGO"
                  height="40px"
                />
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-2 mb-2 px-2">
              <div class="group">
                <input placeholder="ชื่อผู้ใช้" type="text" class="input" />
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-2 mb-2 px-2">
              <div class="group">
                <input placeholder="รหัสผ่าน" type="password" class="input" />
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-12 col-lg-2 mb-2 px-2">
              <div class="form-check mx-2">
                <input
                  class="form-check-input"
                  type="checkbox"
                  value=""
                  id="flexCheckDefault"
                />
                <label
                  class="form-check-label text-secondary"
                  for="flexCheckDefault"
                >
                  จำฉันไว้ในระบบ
                </label>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6 col-lg-2 mb-2">
              <div class="btn-login">
                <button>
                  <span class="shadow"></span>
                  <span class="edge"></span>
                  <span class="front text">เข้าสู่ระบบ</span>
                </button>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6 col-lg-2 mb-2">
            <RouterLink to="/register">
              <div class="btn-register">
                <button>
                  <span class="shadow"></span>
                  <span class="edge"></span>
                  <span class="front text">สมัครสมาชิก</span>
                </button>
              </div>
            </RouterLink>
            </div>
          </div>
        </div>
      </div>

    </section>
        
    
</template>