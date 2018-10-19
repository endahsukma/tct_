# Pertemuan Ke-05

Endah sukma kuncari

JExcel 
https://jspreadsheets.com/jexcel.html
Menginstall Apache pada komputer dengan mengunakan command line administrator
apache yang ada pada xampp dicopy dan dipindahkan pada penyimpanan lain
pada bagian xampp ini file index.html diletakkan pada htdoct kemudian dijalankan pada localhost
perintah yang digunakan cd.. untuk berpindah direktori
lakukan perintah yang sama untuk kedua kalinya dan direktori akan berpindah ke C:\>
perintah selanjutnya cd xampp\apache\bin untuk masuk kedalam bin
melakukan penginstalan ini mengunakan httpd -k install untuk menginstall apache di komputer dan
saat akan memulai untuk menjalankannya dengan ttpd -k start
<html>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jexcel/1.5.7/js/jquery.jexcel.min.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/jexcel/1.5.7/css/jquery.jexcel.min.css" type="text/css" />

<div id="my"></div>

<script>
data = [
    ['jExcel', 'Jquery spreadsheet, javascript spreadsheet, jquery', 181],
    ['Handsontable', 'Another nice javascript spreadsheet plugin', 9284],
    ['Datatables', 'DataTables is a table enhancing plug-in for the jQuery library.', 5164],
];

$('#my').jexcel({ data:data, colWidths: [ 300, 80, 100 ] });
</script>
</html>