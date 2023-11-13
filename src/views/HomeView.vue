<template>
  <div class="container">
  <!-- Navigasi -->
  <nav>
    <h1>Zyka Destotani</h1>
  </nav>
  <!-- Akhir Navigasi -->

  <!-- Content -->
  <main>
    <div class="gambar" >
      <img data-aos="fade-right" src="../assets/zyka.jpg.jpg" alt="">
    </div>

    <div class="content" data-aos="fade-right">
      <h1>My Biodata</h1>
      <br>
      <h3>Nama : Zyka Destotani</h3>
      <h3>Kelas : XII PPLG</h3>
      <h3>Tugas : Pembuatan Portofolio Data Diri</h3>
      <h3>Jurusan : Pengembangan Perangkat Lunak & Game</h3>
      <h3>Sekolah : SMK N 1 Kota Bengkulu</h3>
      <h3>Alamat : JL. Batu sari, RT.1/RW.1, Buahbatu, bojongsoang, Kab. Bandung, Jawabarat</h3>
      <h3>Hobi : Berenang,Membaca Novel Dan Menonton drama korea </h3>
    </div>
  </main>
  <!-- Akhir Content -->

  <!-- About  -->
  <section class="about" data-aos="fade-right">
    <h1>About Me</h1>

    <div class="text">
      <p>Saya adalah siswi dari SMKN 1 Kota Bengkulu. Nama saya Zyka Destotani,biasanya orang memanggil saya dengan sebutin zyka,Saya Memilih Jurusan Sekolah Reakayasa Perangkat Lunak ini karena saya ingin menjadi seorang programing yang berbakat,</p>
     <center><p>_____________________________________________________________________________________________</p></center>
      <p>"Don't just make your wishes a wishful thinking, make them come true and tell the whole world that you can make" "your dreams come true"</p>

    </div>
  </section>
  <!-- Akhir About -->

  <!-- My Sosmed -->
  <section class="sosmed">
    <h1>My Social Media</h1>

    <div class="medsos">
      <div class="fb">
        <a href="https://https://www.facebook.com/Zyka Destotani"><img
            src="https://i.postimg.cc/gcKtc2ZT/1631236822516.png"></a>
      </div>
      <div class="ig">
        <a href="https://instagram.com/zyka_aaaa?igshid=MTBqYzYzZnMwYmtoeg=="><img
            src="https://i.postimg.cc/xCpkgmZZ/1631236822503.png" /></a>
      </div>
      <div class="github">
        <a href="https://www.tiktok.com/@jjzzhyun_20?_t=8h9UouNuvzu&_r=1"><img src="https://i.postimg.cc/jd7WQL48/1631236822493.png" /></a>
      </div>
    </div>
  </section>
  <!-- Akhir My Sosmed -->

  <!-- Contact -->
  <section class="contact">
    <h1>My Contact</h1>

    <form class="format" action="">
      <label>
        Username :
        <br>
        <input type="text" name="username" placeholder="Masukan Nama">
      </label>
      <br><br>
      <label>
        Email :
        <br>
        <input type="email" name="email" placeholder="Masukan Email">
      </label>
      <br><br>
      <label>
        Message :
        <br>
        <textarea name="message" id="message" cols="30" rows="5" placeholder="Masukan Pesan Anda"></textarea>
      </label>
      <br><br>
      <button type="submit">Send</button>
    </form>
  </section>
  <!-- Akhir Contact -->

  <!-- Footer -->
  <footer>
    <h2>Zyka Destotani XII PPLG</h2>
  </footer>
  <!-- Akhir Footer -->
</div>



</template>


<style>
* {
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 18px;
}

body {
  background-color: #ffffff;
}

h1 {
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ;
}


/* Bagian Navigasi */
nav {
  padding: 30px;
  background-color: #fd8700;
  color: rgb(0, 0, 0);
  text-align: center;
}

nav h1 {
  font-size: 2em;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

img {
  width: 50%;
}

main {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  place-items: center;
  margin-top: 20px;
  margin-bottom: 50px;
}

main .gambar {
  padding: 20px;
/*   animation: kanankiri 1.5s; */
}

main .gambar img {
  margin-left: 50px;
  border-radius: 10px;
}

.content {
  margin-left: -200px;
/*   animation: kirikanan 1.5s; */
}

.content h1 {
  font-size: 1.5em;
  text-align: center;
  border-bottom: 2px solid rgb(255, 0, 0);
}

main .content h3 {
  margin-bottom: 10px;
  font-weight: 500;
}
/* Akhir Bagian Navigasi */


/* Bagian About Me */
.about {
  height: 320px;
  background-color: #2ca324;
}

.about h1 {
  padding: 20px;
  text-align: center;
  /* margin-bottom: 5px; */
  font-size: 1.5em;
}

.about .text {
  margin: 10px auto;
  width: 60%;
/*   animation: atasbawah 1.5s; */
}

.about p {
  text-align: center;
  line-height: 30px;
  padding: 10px;
}
/* Akhir Bagian About Me */


/* Bagian Sosmed */
.sosmed {
  height: 200px;
  background-color: #2ca324;
  padding: 20px;
  box-sizing: border-box;
}

.sosmed h1 {
  text-align: center;
  font-size: 1.5em;
  margin: 0 auto;
}

.medsos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(50px, 100px) );
  padding: 35px;
  justify-content: center;
  margin-left: 50px;
/*   animation: bawahatas 1.5s; */
}
/* Akhir Bagian Sosmed */


/* Bagian Contact */
.contact {
  width: 100%;
  margin: 50px auto;
}

.contact h1 {
  font-size: 1.5em;
  text-align: center;
  margin-bottom: 20px;
}

.contact form {
  /* text-align: center; */
  width: 50%;
  margin: auto;
  margin-bottom: 50px;
  padding: 50px;
  border: 2px solid #152D35;
  box-shadow: 0 0 30px rgba(25, 53, 63, 0.5);
}

.contact button {
  width: 100px;
}

.contact input, textarea {
  width: 100%;
}

button {
  width: 50px;
  background-color: #fd0000;
  color: rgb(0, 0, 0);
  border-radius: 5px;
}
/* Akhir Bagian Contact */


/* Bagian Footer */
footer {
  padding: 30px;
  background-color: #fd8700;
  color: rgb(255, 0, 0);
  text-align: center;
}

footer h2 {
  letter-spacing: 2px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
/* Akhir Bagian Footer */


/* Responsive Breakpoint */
/* Tampilan Mobile */
@media screen and (max-width: 600px) {   
  main .gambar img {
    margin-left: inherit;
    width: 70%;
  }
  .content {
    margin-left: inherit;
  }

  .about .text{
    width: inherit;
  }

  .about h1 {
    padding: 5px;
  }

  .about p {
    font-size: 0.8em;
  }

  .contact form {
    width: 250px;
    margin: auto;
  }
  
}



/* My Animation */
@keyframes kirikanan {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes kanankiri {
  0% {
    transform: translateX(-100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes atasbawah {
  0% {
    transform: translateY(-100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes bawahatas {
  0% {
    transform: translateY(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
</style>