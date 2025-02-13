### COMMAND UNTUK MENGGANTI VERSI XRAY
### Hentikan Layanan X-Ray : Hentikan layanan X-Ray untuk mencegah konflik saat mengganti versi.

<pre><code>systemctl stop xray</pre></code>
### Unduh Versi X-Ray Terbaru: Unduh versi X-Ray terbaru dari repository resmi X-Ray

<pre><code>wget https://github.com/xtls/xray-core/releases/download/v1.6.0/xray-linux-64.zip</code></pre>
### Ganti v1.6.0 dengan versi X-Ray yang ingin Anda gunakan

### Ekstrak File X-Ray: Ekstrak file X-Ray yang telah diunduh

<pre><code>unzip xray-linux-64.zip</code></pre>
### Ganti File X-Ray Lama dengan Yang Baru: Ganti file X-Ray lama dengan yang baru

<pre><code>mv xray /usr/local/bin/xray</code></pre>
### Ubah Hak Akses File X-Ray: Ubah hak akses file X-Ray agar dapat dijalankan oleh sistem

<pre><code>chmod +x /usr/local/bin/xray</code></pre>
### Mulai Layanan X-Ray: Mulai layanan X-Ray untuk memastikan bahwa versi baru telah terinstal dengan benar

<pre><code>systemctl start xray</code></pre>
