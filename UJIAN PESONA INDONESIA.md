# Kode Program

```html
<!DOCTYPE html>

<html>

<head>

    <link rel="stylesheet" href="ujian.css">

    <title>Pesona Indonesia</title>

</head>

<body>

   <div class="container">

    <nav class="navbar">

        <img src="./8.jpg" alt="logo">

        <ul>

            <li><a href="#">Beranda</a></li>

            <li><a href="#">Berita</a></li>

            <li><a href="#">About</a></li>

            <li><img src="garis.jpg."></li>

        </ul>

    </nav>

    </div>

      <div class="co-box">

        <div class="box1">

            <h1 class="teks2">Selamat Datang di Indonesia!</h1>

             <p class="teks3">Inilah webite yang berisi Keindahan Alam Indonesia.<br>Selamat menikmati Keindahan Indonesia teman-teman :D</p>

             <button class="tombol2">Klik disini!</button>

        </div>

      </div>

  

        <div class="box2">

            <h1 class="judul" align="center">Berita</h1>

              <div class="berita">

                    <img src="./4.jpg" class="gambar">

                    <h2 class="tk">Pantai Kuta</h2> <br>

                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia

                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,

                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa

                        dan berada di antara daratan benua Asia

                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>

                    <button class="tombol1">Baca selengkapnya >></button>

              </div>

  

              <div class="berita">

                    <img src="./5.jpg" class="gambar">

                    <h2 class="tk">Kebun Tetta</h2> <br>

                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia

                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,

                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa

                        dan berada di antara daratan benua Asia

                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>

                    <button class="tombol1">Baca selengkapnya >></button>

              </div>

  

              <div class="berita">

                <img src="./6.jpg" class="gambar">

                <h2 class="tk">Gunung Bromo</h2> <br>

                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia

                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,

                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa

                    dan berada di antara daratan benua Asia

                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>

                <button class="tombol1">Baca selengkapnya >></button>

              </div>

  

              <div class="berita">

                <img src="./7.jpg" class="gambar">

                <h2 class="tk">Jekadah!</h2> <br>

                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia

                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,

                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa

                    dan berada di antara daratan benua Asia

                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>

                <button class="tombol1">Baca selengkapnya >></button>

              </div>

        </div>

        <div class="box3">

        <h1 class="about">About</h1>

        <div class="teks4">

                <img src="./1.jpg" class="gambar1">

                <p class="teks5">Indonesia, dikenal dengan nama resmi Republik Indonesia

                    atau lebih lengkapnya <br> Negara Kesatuan Republik Indonesia,

                    adalah negara kepulauan di Asia Tenggara yang <br> dilintasi garis khatulistiwa

                    dan berada di antara daratan benua Asia dan Oseania <br> sehingga dikenal sebagai negara lintas benua.</p>

            </div>

        </div>

  

   </div>

</body>

</html>
```

```css
 .container >.kotak{

    width: 100%;

    height: 15%;

    position: fixed;

    background-color: white;

    margin-top: -1%;

    z-index: 1;

}

.container {

    width: 100%;

    margin: 0 auto;

    text-align: center;

}

  

.navbar {

    background-color: #f8f2f2;

    overflow: hidden;

    position: fixed;

    width: 100%;

    height: 50px;

}

  

.navbar img {

    float: left;

    height: 50px;

    padding-left: 2opx;

    padding-bottom: 10px;

    margin-left: 60px;

}

  

.navbar ul {

    list-style-type: none;

}

  

.navbar li {

    display: inline;

    padding: 15px;

}

  

.navbar li a {

    color: rgb(0, 0, 0);

    text-decoration: none;

}

  

.co-box{

    background-image: url(./3.jpg)

}

  

.box  >.tulisan{

    margin-left: 38%;

    font-size: 18px;

    padding-top: 40px;

   font-family: 'Segoe UI';

}

  

.logo{

    width: 100px;

    height: 50px;

    float: left;

}

  
  

.samadengan{

  width: 30px;

  height: 15px;

  margin-left: 220px;

  float: left;

  margin-top: -36px;

  

}

  

.box1{

    padding-bottom: 20%;

    padding-top: 10%;

    background-image: url(hero-image.jpg);

    width: 100%;

    height: 18%;

    margin-bottom: 40px;

    background-size:cover ;

}

  

.teks3{

    text-align: center;

    font-size: 15px;

    font-family: 'Segoe UI';

    margin-top: -10px;

}

  

.teks33{

    text-align: center;

    font-size: 15px;

    font-family: 'Segoe UI';

    margin-top: -5px;

    margin-right: 7px;

}

  

.teks2{

    margin-top: 150px;

    text-align: center;

    font-family: 'Segoe UI';

}

  

.teks2{

  color: white;

  text-align: center;

  font-family: 'Segoe UI';

}

  

.tombol2 {

  color: white;

  background-color: blue;

  width: 110px;

  height: 50px;

  margin-left: 45%;

  border-radius: 5px;

  box-shadow: 2px 2px 2px 2px blue;

  border: none;

  position: flex -15px;

}

  

.tombol2:hover {

  background-color: burlywood;

  color: black;

  box-shadow: 2px 3px 2px 3px gray;

  transition: all 0.5s ease-in;

}

  

.berita {

  margin-top: 150px;

    width: 275px;

    height: 520px;

    border-radius: 15px;

    box-shadow: 5px 4px 10px 4px #c7c1c1;

    float: left;

    margin: 16px;

    font-size: 15px;

    padding: 10px 0px 20px 20px;

  }

  

.tk{

    color: blue;

    font-family: 'Segoe UI';

   margin-bottom: 1px;

   margin-left: 3px;

  }

  

.gambar{

   width: 265px;

   border-radius: 20px;

   height: 170px;

  }

  

.tombol1{

    border: none;

    background-color: blue;

    width: 194px;

    height: 50px;

    color:white;

    box-shadow: 2px 3px 2px 3px #4c86df;

    border-radius: 10px;

    margin-top: 1px;

    margin-left: 30px;

  }

  

.tombol1:hover {

    background-color: burlywood;

    color: black;

    box-shadow: 2px 3px 2px 3px gray;

    transition: all 0.3s ease-in;

  }

  

  /*.tetx{

    margin-top: -1px;

    padding: 10px 20px 20px 20px;

    font-family: 'Segoe UI';

  }*/

  

.box3{    

    margin-top: 100px;

    background-color: blue;

    height: 360px;

    width: 100%;

    display: flex;

    flex-direction: column;

  }

  

.teks4 {

    display: flex;

    flex-direction: row;

}

  

.gambar1{

    width: 200px;

    height: 200px;

    border-radius: 100px;

    margin-left: 15%;

    margin-top: 50px;

    filter: grayscale(100%);

    margin-top: 0px;

}

  

.about{

    color: white;

    text-align: center;

    font-family: 'Segoe UI';

    padding-top: 35px;

    margin-top: -5px;

    margin-left: -10px;

  }

  

.teks5{

    text-align: justify;

    margin-top: 50px;

    font-family: 'Segoe UI';

    color: white;

    margin-left: 5%;

    display: flex;

    flex-direction: column;

  }

  .tambahan {

    margin-top: 650px;

    background-color: cadetblue;

    height: 500px;

    width: 100%;

    display: flex;

    flex-direction: row;

    justify-content: space-around;

  }

  

.tambahan > h1 {

    color: black;

    font-family: 'Segoe UI';

    padding-top: 25px;

    padding-left: 30%;

  }

  

  .judultambahan {

    margin-left: -645 px;

    margin-right: 10%;

    margin-top: 5px;

    color: white;

    text-align: center;

    position: relative;

    left: 350px;

  }

  

  .kesatuu {

    margin-top: 150px;

      width: 270px;

      height: 300px;

      border-radius: 15px;

      font-size: 15px;

      padding: 10px 0px 20px 20px;

      margin-top: 130px;

      margin-left: 35px;

      margin-bottom: -60px;

      position: relative;

      left: -380px;

      right: -350px;

    }

  .peta1{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 0px;

     margin-left: -15px;

     text-align: center;

    }

  

    .peta2{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 1px;

     margin-left: -15px;

     text-align: center;

    }

  

    .peta3{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 0px;

     margin-left: -15px;

     text-align: center;

    }

  .kesatu{

     width: 265px;

     border-radius: 20px;

     height: 170px;

     margin-top: 10px;

     margin-right: 20px;

    }

  .tomboltambahan{

      border: none;

      background-color: blue;

      width: 194px;

      height: 50px;

      color:white;

      box-shadow: 2px 3px 2px 3px #4c86df;

      border-radius: 10px;

      margin-top: 20px;

      margin-left: 35px;

    }

  .tomboltambahan:hover {

      background-color: burlywood;

      color: black;

      box-shadow: 2px 3px 2px 3px gray;

      transition: all 0.5s ease-in;

    }

  
  
  
  
  

/*@media (max-width: 701px){

    .tombol2 {

      margin-left: 275px;

    }

  

    .logo {

      margin-left: 150px;

    }

  

    .tulisan {

      margin-left: 150px;

    }

  

    .gambar1 {

      margin-left: 20px;

    }

  

    .teks5 {

      margin-top: 25px;

      margin-right: 30px;

    }

}

  

/*.{

    width: 145px;

    height: 200px;

    border-radius: 200px;

    margin-left: -150%;

    margin-top: 10px;

   display: flex;

   margin-top: 100px;  

   align-items: center;

  }

  

.deskripsi{

    margin-left: -350%;

    text-align: center;

    margin-top: 40px;

    font-family: 'Segoe UI';

    color: white;

    border: 10px;

    border-color: white;

    border-radius: 15px;

  }

  

  .satu {

    width: 100px;

  

  }

  

  .dua {

    width: 100px;

    float: left;

  }

  

  .tiga {

    width: 100px;

    float: left;

  }*/
```

# Hasil

![pesona](pesona.png)
![pesona](pt2.png)
![pesona](pt3.png)
