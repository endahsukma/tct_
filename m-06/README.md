# Pertemuan ke-06

*Endah sukma kuncari*
Membuat Endpoint 

Langkah yang harus dilakukan yaitu

	1. Menginstall aplikasi NodeJs
	Link : https://nodejs.org/en/download/
	
	2. Membuat file berinteraksi dengan js untuk direktori sama menamai dengan pertemuan6\
		Saya menginstall nodejs ini di F dan direktori yang saya namai pertemuan6
		
	3. Memanggil file js di cmd dengan code
		var http = require('http'); 
		http.createServer(function (req, res) {   
		res.writeHead(200, {'Content-Type': 'text/plain'});   
		res.end('Hello : ENDAH SUKMA KUNCARI\n'); }).listen(1337, '127.0.0.1'); 
		onsole.log('Server running at http://127.0.0.1:1337/');
		membuat file dengan nama hello.js yang menampilkan Hello ENDAH SUKMA KUNCARI
		
	4. Memanggil di web browser
		http://127.0.0.1:1337/
		
	5. Menginstall framework express
	   - Dengan mengunakan perintah npm install -g express
	   perintah ini untuk menginstall express
	   - Perintah selanjutnya npm install -g express -generator
	   perintah yang kedua mengunakan express generator
	6. Membuat project disini saya mengunakan perintah express hello(menyesuaikan) -e
	
	7. menginstall dependencies dengan perintah
		cd hello(nama project) && npm install
		masuk ke project yang tadi saya namai dengan hello dan perintah untuk menginstall
		
	8. Mengaktifkan npm dengan perintah npm start
		setelah berhasil di install kemudian akan melakukan pengaktifan npm
		
	9. Menjalankan file dengan perintah nodejs
	Membuat file dengan nama hello2.js
	code 
	const express = require('express')
	const app = express()
	const port = 3000

	app.get('/', function (req, res) {
	res.jsonp({ user: 'endah' });
	})

	app.listen(port, () => console.log(`Example app listening on port ${port}!`))
	
	file diatas disimpan dan dijalankan lagi pada cmd dengan perintah node hello2.js(menyesuaikan)
	 
