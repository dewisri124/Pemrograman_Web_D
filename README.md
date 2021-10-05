# Pemrograman_Web_D
Dewi Sri Wahyuni
<!DOCTYPE HTML>
<html>
	<head>
    </script>
    			<title>
        		Looping Array Javascript 
				Dewi Sri Wahyuni        </title>
    </head>
<style>.coding{border-left:solid 10px #4c90a6;padding-left:10px;border-bottom:solid 1px #4c90a6;border-top:solid 1px #4c90a6;border-right:solid 1px #4c90a6;border-top-right-radius:5px;border-bottom-right-radius:5px;background-color:#f5f5f5}pre{border-left:solid 10px #4c90a6;padding-left:10px;border-bottom:solid 1px #4c90a6;border-top:solid 1px #4c90a6;border-right:solid 1px #4c90a6;border-top-right-radius:5px;border-bottom-right-radius:5px;background-color:#f5f5f5;overflow-x:scroll;max-width:870px}body{color:#000}</style>
<style>.title{background-image:-webkit-gradient(linear,left top,left bottom,color-stop(0%,#9bc7e2),color-stop(100%,#9bc7e2));background-image:-webkit-linear-gradient(#fff,#9bc7e2);-webkit-background-clip:text;-webkit-text-fill-color:transparent;color:#fff;position:relative;text-shadow:none}.title:before{background:none;content:attr(data-text);left:0;position:absolute;text-shadow:0 3px 0 rgba(0,0,0,.3);top:0;z-index:-1}.fona{color:#fff}.foni{position:absolute;padding-top:15%;padding-left:3%;text-shadow:-1px 0 black , 0 5px black , 1px 0 black , 0 -1px black}.kate{position:absolute;bottom:0;right:0;padding-right:3%}.icon{position:absolute;padding-top:3%;padding-left:3%;padding-right:3%}</style>

<script>
jQuery(document).ready(function($) {
  $('.popup').click(function(event) {
    var width  = 575,
        height = 400,
        left   = ($(window).width()  - width)  / 2,
        top    = ($(window).height() - height) / 2,
        url    = this.href,
        opts   = 'status=1' +
                 ',width='  + width  +
                 ',height=' + height +
                 ',top='    + top    +
                 ',left='   + left;
 
    return false;
  });
   });
</script>
	<body class="is-preload">

		<!-- Wrapper -->
			<div id="wrapper">

				<!-- Main -->
					<div id="main">
						<div class="inner">

                            <br>
							
							<div id="content">
	<style>.title{background-image:-webkit-gradient(linear,left top,left bottom,color-stop(0%,#9bc7e2),color-stop(100%,#9bc7e2));background-image:-webkit-linear-gradient(#fff,#9bc7e2);-webkit-background-clip:text;-webkit-text-fill-color:transparent;color:#fff;position:relative;text-shadow:none}.title:before{background:none;content:attr(data-text);left:0;position:absolute;text-shadow:0 3px 0 rgba(0,0,0,.3);top:0;z-index:-1}.fona{color:#fff}.foni{position:absolute;padding-top:15%;padding-left:3%;text-shadow:-1px 0 black , 0 5px black , 1px 0 black , 0 -1px black}.kate{position:absolute;bottom:0;right:0;padding-right:3%}.icon{position:absolute;padding-top:3%;padding-left:3%;padding-right:3%}</style>
<section>
    <header class="main">
        <h1>Looping Array Javascript</h1>
    </header>
	<div style="color:#999;"><i>Tanggal : 05 Okt 2021, Pemrograman Web D, Create By 5026201004 : </i></div>
    <span class="image main" style="position:relative">
				<strong class="icon"><h1 class="title"><Pemrograman Web D></h1></strong>
		<strong class="foni"><h1 class="title">Looping Array Javascript</h1></strong>
		<strong class="kate"><h2 class="title">Dewi Sri Wahyuni</h2></strong>
		    	<img src="fiks.JPEG" alt="Dewi Sri"width="600" height="300"/>
    </span>

    <p>Looping adalah sebuah metode perulangan dimana bisanya perulangan tersebut akan menghasilakan sebuah data berurutan, misalkan looping angka numerik 1 sampai dengan 10 maka looping akan mencetak 1 2 3 4 5 6 7 8 9 10 jika dalam bahasa pemprograman javascript anda bisa melakukan atau menulis script dibawah ini.</p>
<pre>for (i = 1; i &lt;= 10; i++){<br/> <br/>}</pre>
<p>i&nbsp; &nbsp; &nbsp; : adalah variabel yang di isi nilai 1</p>
<p>&lt;=&nbsp; : adalah operator lebih dari sama dengan&nbsp;</p>
<p>i++ : adalah fungsi untuk menambah 1 variabel i</p>
<p>Dari contoh script di atas hanya menampilkan angka 1 sampai dengan 10, karena di situ ada operator yang berjalan hanya ketika nilai i dibawah atau sama dengan nilai 10.</p>
<p>Sekarang kita akan coba menggunakan looping dengan array, apa itu array, array adalah sebuah kumpulan data, maka dari itu nilai array kita ambil ada berapa data yang ada di dalam array tersebut, oke mari kita langsung ke contoh scriptnya.</p>
<pre>&lt;script&gt;<br/>var cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"];<br/>var text = "";<br/>var i;<br/>for (i = 0; i &lt; cars.length; i++) {<br/> text += cars[i] + "&lt;br&gt;";<br/>}<br/>document.getElementById("demo").innerHTML = text;<br/>&lt;/script&gt;<br/><br/>output :<br/><br/>BMW<br/>Volvo<br/>Saab<br/>Ford<br/>Fiat<br/>Audi</pre>
<p>Nilai array akan di awali dari nilai 0 (nol) maka dari itu variabel i kita isi dengan angka nol kemudian operator dari pembatas pencetakan data kita menggunakan fungsi <strong>cars.length</strong>&nbsp;untuk mengetahui jumlah data array yang ada.</p>
<p>Mungkin hanya itu yang bisa kami sampaikan semoga bermanfaat</p>	
</html>
