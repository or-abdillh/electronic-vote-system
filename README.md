### Electroic Vote System
Studi kasus : HIMA Teknik Informatika Politeknik Hansur

![banner](./assets/banner.png)

---

## About

Electronic Vote System atau ~~EVoting~~ adalah sistem pemungutan suara elektronik berbasis website yang dibangun untuk mempermudah kegiatan pemilihan ketua dan wakil ketua umum HIMA TI Polihasnur yang sebelumnya masih menggunakan Google Form.

Sistem ini dibangun terdiri atas tiga buah aplikasi yang memiliki fungsi masing - masing diantaranya adalah :

- Evote admin
	 Adalah aplikasi yang khusus digunakan oleh administrator atau pihak yang memiliki wewenang dalam melakukan monitoring dan menjalankan setiap fungsi pada aplikasi

- Evote Client
	 Adalah aplikasi yang khusus digunakan oleh para pemilih yang telah memiliki akses berupa username dan password yang sudah terdaftar didalam sistem

- Evote API
	 Adalah aplikasi server atau REST API khusus yang digunakan untuk menghubungkan aplikasi client dan admin ke database maupun server

## Case study

Studi kasus yang ada pada aplikasi ini adalah berawal dari keikutsertaan saya dalam kepengurusan HIMA TI Polihasnur tahun 2020 yang mana pada saat itu belum memiliki sistem evoting mereka sendiri dan masih mengandalkan layanan Google Form.

Saya mendapati banyak faktor yang menyebabkan HIMA TI Polihasnur saat itu belum memiliki sistem evoting mereka sendiri, yaitu :

- Kualitas dan kuantittas SDM
		Menurut pengamatan saya inilah faktor paling berdampak karena jika SDM yang dimiliki sedikit ditambah dengan hardskill yang bisa dikatak kurang mempuni akan sulit untuk memulai pengembangan sistem evoting sendiri

- Bukan prioritas program kerja
- Berada pada zona nyaman ketika menggunakan layanan Google Form

### Solutions

Dari studi kasus diatas saya memiliki solusi untuk mengembangkan sistem evoting yang mudah dimaintenance serta mudah dikembangkan

### Development flow

Dalam perancangan saya memecah sistem ini menjadi tiga aplikasi yang berdiri sendiri, bertujuan untuk memudahkan ketika dilakukan maintenance mauppun menambahkan fitur baru kedalam salah satu aplikasi

Adapun urutan pengembangan aplikasi ini adalah sebagai berikut :

- Tahap 1 : Evote Client
	- Wireframing aplikasi evote client
	- Convert wireframe sebagai final design concept evote client
	- Slicing design kedalam real interface
	- Merancang structure database
	- Membuat flowchart dan DFD dari rancangan aplikasi evote api
	- Mengembangkan evote api untuk keperluan evote client   

- Tahap 2 : Evote Admin
		- Searching tempalate admin yang sesuai
		- Mengembangkan evote admin berdasarkan kebutuhan 
		- Mengembangkan evote api untuk keperluan evote admin

		
