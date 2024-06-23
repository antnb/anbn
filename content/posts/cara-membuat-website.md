---
title: Cara Membuat Website Gratis Dengan WordPress Selfhosted
image: images/website.jpg
caption: 
date: 2024-06-22T07:18:48+00:00
---

Cara membuat website sebenarnya tidaklah susah WordPress. yang kita perlukan hanyalah sebuah domain name dan server hosting gratis yang akan digunakan untuk menyimpan file untuk keperluan website.

WordPress cms adalah pilihan yang paling populer saat ini, diperkirakan telah ada sekitar 60 juta website dibuat menggunakan cms wordpress sebagai platform management systemnya.

Keuntungan yang didapat dari membuat website dengan wordpress antara lain ialah : selain gratis sangat mudah untuk memanage website. cara membuat website dengan wordpress tidak memerlukan banyak keahlian seperti php,html dan css,dan lain nya

## Langkah membuat website menggunakan wordpress

 * [Pemilihan Domain Name](#belidomain)
 * [Memilih hosting](#hosting)
 * [Setup domain name](#setup-domain)
 * [Instalasi wordpress](#instalasi-wordpress)
 * [Kostumisasi dan finishing](#kostumisasi-dan-finishing)

## <span id="belidomain">Pemilihan Domain Name</span>

Dalam tulisan cara membuat website dengan wordpress ini, maka hal pertama yang kita butuhkan adalah Sebuah **domain name** ,untuk pemilihan domain name terdapat 2 pilihan.

Yaitu menggunakan domain name gratis atau menggunakan TLD berbayar (untuk extensi .COM sekitar 98ribu pertahun ) .untuk keperluan tutorial ini saya menggunakan pilihan subdomain name gratis dari freeavailabledomains.com

{{< figure src="/images/domain-name.jpg" title="membuat domain name untuk website" >}}



Buat Account Gratis Di http://freeavailabledomains.com/en ,setelah itu silahkan pilih domain name yang Dikehendaki kemudian klik Check out ,silahkan buka email untuk mengaktifkan account kita.pada tahap ini domain tersebut belum dapat diakses atau dibuka dikarenakan belum ada dns yang di setup pada domain name kita</section> <section> 

## Memilih hosting

Setelah Proses Pendaftaran domain selesai,kita berlanjut pada proses kedua dalam seri tutorial cara membuat website ini yaitu pemilihan hosting,sama hal nya dengan pemilihan domain ada 2 pilihan yaitu menggunakan hosting gratis atau menggunakan hosting berbayar (biaya kontrak hosting berbayar bervariasi mulai dari 300 ribu sampai 1.5 juta pertahun).

Untuk keperluan dari cara membuat website dengan wordpress ini saya menggunakan pilihan hosting gratis dari nazuka.net

{{< figure src="/images/setuphostingwordpress.jpg" title="pendaftaran hosting website" >}}

Lakukan Proses Pendaftaran Untuk mendapatkan Account hosting untuk website wordpress kita dengan membuka URL http://nazuka.net/ .pada pilihan Domain ,masukan Domain name yang telah kita daftarkan sebelumnya kemudian klik create setelah itu kita masuk pada kolom detail untuk mendapatkan detail dns yang akan kita arahkan ke domain Name kita</section> <section> 

## Setup domain name

{{< figure src="/images/pointdnswebsitewordpress.jpg" title="setup dns hosting" >}}


Pada Tahapan cara membuat website Ini ,Yang Perlu dicatat adalah Bagian Pada Hosting Name Server Detail saja,detail tersebut akan dibutuhkan pada tahapan selanjutnya.

Setelah kedua langkah diatas telah selesai, kita masuk pada tahap selanjutnya yaitu melakukan proses setup domain dengan mengarahkan dns dari hosting ke panel domain name kita setup dns pada cpanel


{{< figure src="/images/pointingdns.jpg" title="setup dns hosting" >}}

Pada Panel domain manager silahkan Klik domain yang akan kita setup,kemudian pilih &#8220;NAME SERVER&#8221; pada kolom ini masukan name server detail yang kita dapat dari penyedia hosting kita atau pada langkah no 2 di atas,pada tutorial cara membuat website ini penyedia hosting yang kita gunakan (nazuka.net) menggunakan 4 name server sedangkan pada domain kita hanya diberikan 2 form saja .

Jika mendapatkan kasus seperti ini tidak perlu bingung ,cukup masukan dns yang teratas saja. lihat pada gambar untuk detail atau bisa melihat video berikut ini

Pada tahap ini proses Setup domain name dan pointing dns telah selesai . namun saat ini website masih belum bisa diakses dikarenakan proses propagasi di atas,proses ini biasanya memakan waktu paling lama sekitar 2&#215;24 jam

{{< figure src="/images/tampilanwebsite.jpg" alt="tutorial membuat website telai selesai" >}}


## Instalasi wordpress

Setelah setup domain dan dns telah selesai,saatnya kita mempersiapkan bahan yang diperlukan untuk membuat website kita mendownload wordpress terbaru .

Unzip file yang telah kita download menggunakan winzip atau winrar kemudian mengupload file yang telah kita unzip tadi menggunakan FTP software seperti filezilla.

Setelah itu membuat database untuk wordpress caranya yaitu masih di control panel hosting,klik pada &#8220;MySQL Database&#8221; kemudian silahkan isi form satu persatu dan klik &#8220;Create&#8221;

{{< figure src="/images/membuatdatabasewordpress.jpg" alt="membuat website database" >}}


setup database untuk website

{{< figure src="/images/databasewordpress.jpg" alt="membuat database user dan password" >}}


Setelah itu saatnya melakukan proses instalasi wordpress dengan automatic install caranya yaitu dengan mengakses domain kita melalui web browser membuat website wordpress tahap 1.

Setelah kita akses melalui web browser kita akan dihadapkan dengan tampilan seperti di atas ,hal tersebut dikarenakan file configurasi website wordpress (wp-config.php) belum terkonfigurasi sesuai dengan detail database yang telah kita siapkan sebelumnya .

Jika tidak ingin melalui proses instalasi ini pada saat akan mengupload file ke server hosting,bisa mengedit file wp-config.php sesuai dengan database yang telah disiapkan sebelumnya klik &#8220;Create a Configuration File&#8221;

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://1.bp.blogspot.com/-rpAezgxbAPA/Uzd9xWdf4qI/AAAAAAAAAQs/UjdYORH_lPs/s1600/instalasi+websitemenggunakanwordpress.jpg"><img decoding="async" src="https://1.bp.blogspot.com/-rpAezgxbAPA/Uzd9xWdf4qI/AAAAAAAAAQs/UjdYORH_lPs/s1600/instalasi+websitemenggunakanwordpress.jpg" alt="setup admin website" border="0" data-original-height="398" data-original-width="866" /></a>
</div>

Setelah itu isikan form yang ada sesuai dengan database yang telah disiapkan kemudian klik &#8220;Submit&#8221; pastikan semua detail telah diisikan dengan benar

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://3.bp.blogspot.com/-ZsxA4-X7T8k/Uzd_ndSfigI/AAAAAAAAAQ4/cwTVPGQnVe0/s1600/instalasi+databasewordpress.jpg"><img decoding="async" src="https://3.bp.blogspot.com/-ZsxA4-X7T8k/Uzd_ndSfigI/AAAAAAAAAQ4/cwTVPGQnVe0/s1600/instalasi+databasewordpress.jpg" alt="pembuatan website telah selesai" border="0" data-original-height="474" data-original-width="775" /></a>
</div>

Setelah wordpress telah selesai dikonfigurasikan klik &#8220;Run The Install&#8221;

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://4.bp.blogspot.com/-tHqO551UxCk/UzeAbZ0gibI/AAAAAAAAARA/fiLP5pB07Is/s1600/instalasiwebsitewordpresstelahselesai.jpg"><img decoding="async" src="https://4.bp.blogspot.com/-tHqO551UxCk/UzeAbZ0gibI/AAAAAAAAARA/fiLP5pB07Is/s1600/instalasiwebsitewordpresstelahselesai.jpg" alt="" border="0" data-original-height="346" data-original-width="835" /></a>
</div>

Kemudian Isi form selanjutnya sesuai dengan kebutuhan .harap diperhatikan pada kolom USERNAME dan PASSWORD harus diingat ingat karena itu adalah detail admin yang akan digunakan seterusnya.  
setelah pengisian form selesai silahkan klik &#8220;Install WordPress&#8221;

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://4.bp.blogspot.com/-s1T2N1jIBfs/UzeBGBiVFfI/AAAAAAAAARM/QeDzMtmb4vk/s1600/websitewordpress.jpg"><img decoding="async" src="https://4.bp.blogspot.com/-s1T2N1jIBfs/UzeBGBiVFfI/AAAAAAAAARM/QeDzMtmb4vk/s1600/websitewordpress.jpg" alt="" border="0" data-original-height="526" data-original-width="768" /></a>
</div>

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://1.bp.blogspot.com/-zyR6r4_SwfI/UzeCRq6lcZI/AAAAAAAAARU/zac3gORa8h4/s1600/membuatwebsitemenggunakanwordpress.jpg"><img decoding="async" src="https://1.bp.blogspot.com/-zyR6r4_SwfI/UzeCRq6lcZI/AAAAAAAAARU/zac3gORa8h4/s1600/membuatwebsitemenggunakanwordpress.jpg" alt="" border="0" data-original-height="392" data-original-width="816" /></a>
</div>

Pada Tahap Ini proses cara membuat website dengan wordpress telah selesai</section> <section> 

## Kostumisasi dan finishing

Setelah proses instalasi website selesai saatnya masuk ke tahap kostumisasi dan finishing .untuk dapat mengkustomisasi website kita ataupun menambahkan konten kedalam website kita silahkan mengakses back end admin dengan membuka url http://wordpress141.tld.cc/wp-login.php

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://3.bp.blogspot.com/-TE3t1I1SXHE/UzeEPhK1XJI/AAAAAAAAARg/zGt0I5qJsz0/s1600/adminbackendwordpress.jpg"><img decoding="async" src="https://3.bp.blogspot.com/-TE3t1I1SXHE/UzeEPhK1XJI/AAAAAAAAARg/zGt0I5qJsz0/s1600/adminbackendwordpress.jpg" alt="wordpress admin login" border="0" data-original-height="496" data-original-width="660" /></a>
</div>

kemudian masukan detail untuk user dan password admin dan klik &#8220;Login&#8221;

<div style="clear: both;">
  <a style="display: block; padding: 1em 0; text-align: center;" href="https://4.bp.blogspot.com/-uzeriWCv5_U/UzeEztTAINI/AAAAAAAAARo/fIheLIbgeBI/s1600/dashboardadminwordpress.jpg"><img decoding="async" src="https://4.bp.blogspot.com/-uzeriWCv5_U/UzeEztTAINI/AAAAAAAAARo/fIheLIbgeBI/s1600/dashboardadminwordpress.jpg" alt="website menggunakan wordpress" border="0" data-original-height="528" data-original-width="1275" /></a>
</div></section>

 [1]: http://antnb.blogspot.com/#domain
 [2]: http://antnb.blogspot.com/#Hosting
 [3]: http://antnb.blogspot.com/#setup_dns
 [4]: http://antnb.blogspot.com/#instal_wordpress
 [5]: http://antnb.blogspot.com/#Kostumisasi