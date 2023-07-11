# uas_designweb
"index3.html"
<!DOCTYPE html>
<html>
<head>
  <title>website uas desain web</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      padding: 20px;
      color: #1dcdd3;
      text-align: center;
    }
    nav {
      background-color: #b3acee;
      padding: 10px 20px;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
    }
    nav ul li {
      margin-right: 10px;
    }
    nav ul li a {
      color: #333;
      text-decoration: none;
      padding: 5px 10px;
      border-radius: 5px;
    }

    .images {
      width: 800px;
      height: 800px;
    }

    .img-fluids {
      max-width: 100%;
    }

    .img-fluid {
      height: 900px;
      width: 900px;
    }
    .container {
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      margin-bottom: 20px;
    }
    .cta-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: #12dbcb;
      text-decoration: none;
      border-radius: 5px;
      font-size: 18px;
    }
    footer {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>arifin hidayatullah</h1>
  </header>
  <nav>
    <ul>
      <li><a href="#home">Beranda</a></li>
      <li><a href="#about">Tentang Kami</a></li>
      <li><a href="#services">Layanan</a></li>
      <li><a href="#contact">Kontak</a></li>
      <li><a href="login.html">Login</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <div class="beranda" id="home">
    <section class="hero bg-secondary text-light py-5">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <h1 class="display-4">cucian arif jaya</h1>
            <p class="lead">budidayakan malas mencuci karena itu tugas kami</p>
            <img src="cucian.jpg" alt="Tentang Kami" class="img-fluids">
          </div>
        </div>
      </div>
    </section>
    </div>
<!-- About Section -->
  <div class="container">
    <h1>Selamat Datang di cucian arif jaya!</h1>
    <p>kami disini mempunyai macam variasi dalam bentuk pencucian yaitu dari segi proses sampai finishing di tahap selesai</p>
    <a href="#" class="cta-button">Mulai Sekarang</a>
  </div>
  <div class="about" id="about">
    <section class="about py-5">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <h2>Tentang Kami</h2>
            <p>kami juga mempunyai harga berbeda dan diskon bagi anda yg mempunyai kartu member atau pelanggan setia .</p>
          </div>
          <!-- layanan Section -->
          <div class="col-lg-6">
            <img src="member.jpg" alt="Tentang Kami" class="img-fluid" >
          </div>
          <div class="services" id="services">
            <section class="services bg-light py-5">
              <div class="container">
                <h2>Layanan Kami</h2>
                <div class="row">
                  <div class="col-lg-4">
                    <div class="card mb-4">
                      <img src="layanan 1.jpeg" alt="Layanan 1" class="images">
                      <div class="card-body">
                        <h5 class="card-title">Layanan 1</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-4">
                    <div class="card mb-4">
                      <img src="ly1.jpg" alt="Layanan 2" class="card-img-top">
                      <div class="card-body">
                        <h5 class="card-title">Layanan 2</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-4">
                    <div class="card mb-4">
                      <img src="ly2.jpg" alt="Layanan 3" class="card-img-top">
                      <div class="card-body">
                        <h5 class="card-title">Layanan 3</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
            </div>
        </div>
      </div>
    </section>
    </div>
<!-- kontak Section -->
  <footer>
    <p>website arifin. All rights reserved.</p>
    <div class="contact" id="contact">
        <section class="contact bg-primary text-light py-5">
          <div class="container">
            <div class="row">
              <div class="col-lg-6">
                <h2>Kontak Kami</h2>
                <p>Hubungi kami untuk informasi lebih lanjut.</p>
                <ul class="list-unstyled">
                  <li>
                    <strong>Alamat:</strong> kecamatan wongsorejo,desa bajulmati,dusun badolan
                  </li>
                  <li>
                    <strong>Email:</strong> arif@gmail.com
                  </li>
                  <li>
                    <strong>Telepon:</strong> 123321456654
                  </li>
                </ul>
              </div>
              <div class="col-lg-6">
                <form>
                  <div class="mb-3">
                    <label for="name" class="form-label">Nama</label>
                    <input type="text" class="form-control" id="name" placeholder="Masukkan nama Anda">
                  </div>
                  <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Masukkan alamat email Anda">
                  </div>
                  <div class="mb-3">
                    <label for="message" class="form-label">Pesan</label>
                    <textarea class="form-control" id="message" rows="5" placeholder="Masukkan pesan Anda"></textarea>
                  </div>
                  <button type="submit" class="btn btn-light">Kirim Pesan</button>
                </form>
              </div>
            </div>
          </div>
        </section>
        </div>
      
  </footer>
</body>
</html>

"login.html"
<html lang="en-US">
<head>
  <meta charset="utf-8" />
  <title>Login</title>
  <link rel="stylesheet" href="/css/styles.css" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:400,700" />
</head>
<style>
  body {
    background-image: url(https://www.goodscoop.id/wp-content/uploads/2022/11/grafity-gc90c6ab4a_1280.jpg);
    color: #606468;
    font: 87.5%/1.5em 'Open Sans', sans-serif;
    margin: 0;
    height: 100vh;
  }
  
  input {
    border: none;
    font-family: 'Open Sans', Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5em;
    padding: 0;
  }
  
  p {
    line-height: 1.5em;
  }
  
  after { clear: both; }
  
  #login {
    margin: 50px auto;
    width: 320px;
  }
  
  #login form {
    margin: auto;
    padding: 30px;
    border-radius: 10px;
    background: #22272a;
  }
  
  .input{
    background-color: #3b4148;
    border-radius:10px;
    color: #a9a9a9;
    margin-bottom: 1em;
    padding: 0 16px;
    width: 100%;
    outline: 0;
    height: 50px;
  }
  .submitbtn {
    background: #0c787d;
    border: 0;
    width: 100%;
    height: 40px;
    border-radius: 10px;
    color: white;
    cursor: pointer;
    transition: background 0.3s ease-in-out;
  }
  .submitbtn:hover {
    background: #076064;
  }
  
</style>
<body style=" height:100%;display:flex ; justify-content: center; align-items: center;">
  <div id="login">
    <form name="form-login">
      <input type="text" class="input" id="user" placeholder="Username" />
      <input type="password" class="input" id="pass" placeholder="Password" />
      <button type="submit" class="submitbtn">Login</button> <p></p>
      <p> Belum punya akun?
        <a href="register.html">Register di sini</a>
      </p>
    </form>
  </div>
</body>
</html>

"register.html"
<html lang="en-US">
<head>
  <meta charset="utf-8" />
  <title>Register</title>
  <link rel="stylesheet" href="/css/styles.css" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:400,700" />
</head>
<style>
  body {
    background-image: url(https://blue.kumparan.com/image/upload/v1634025439/72a5e281b6844fdce3b267a2e3ba8e3f4c6cc0b545431a6c35c9fe3b471febfa.jpg);
    color: #606468;
    font: 87.5%/1.5em 'Open Sans', sans-serif;
    margin: 0;
    height: 100vh;
  }
  
  input {
    border: none;
    font-family: 'Open Sans', Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5em;
    padding: 0;
  }
  
  p {
    line-height: 1.5em;
  }
  
  after { clear: both; }
  
  #login {
    margin: 50px auto;
    width: 320px;
  }
  
  #login form {
    margin: auto;
    padding: 30px;
    border-radius: 10px;
    background: #22272a;
  }
  
  .input{
    background-color: #3b4148;
    border-radius:10px;
    color: #a9a9a9;
    margin-bottom: 1em;
    padding: 0 16px;
    width: 100%;
    outline: 0;
    height: 50px;
  }
  .submitbtn {
    background: #0c787d;
    border: 0;
    width: 100%;
    height: 40px;
    border-radius: 10px;
    color: white;
    cursor: pointer;
    transition: background 0.3s ease-in-out;
  }
  .submitbtn:hover {
    background: #076064;
  }
  
</style>
<body style=" height:100%;display:flex ; justify-content: center; align-items: center;">
  <div id="login">
    <form name="form-login">
      <input type="text" class="input" id="user" placeholder="Username" />
      <input type="password" class="input" id="pass" placeholder="Password" />
      <input type="Email" class="input" id="pass" placeholder="Email" />
      <button type="submit" class="submitbtn">Register</button> <p></p>
      <p> Sudah punya akun?
        <a href="index3.html">Login di sini</a>
      </p>
    </form>
  </div>
</body>
</html>
