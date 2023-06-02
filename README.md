Butonun üstüne iki tane TextFormField oluşturdum. 
TextFormField’a girilen değerleri tutması için iki tane TextEditingController oluşturdum.
Navigator.pushNamed’in arguments parametresini aktif ettim.
TextEditingController ile aldığım değerleri oluşturduğum VeriModeli sınıfının içinde tanımladığım kullaniciAdi ve sifre değişkenlerine arguments parametresi ile verdim.
Navigator.pushNamed çalıştığında artık TextFormField’a gireceğimiz bu değerler diğer ekrana iletilecek.
Daha önce oluşturduğumuz VeriModeli tipinde bir değişken yazdım.
İsmini iletilenArgumanlar koyuyorum. ModalRoute ile aşağıdaki şekilde, önceki ekrandan Navigator.pushNamed’in arguments parametresi ile buraya iletilen değerlere erişip, iletilenArgumanlar değişkenine atıyoruz.
Ve uygulamam hazır hale geliyor.


Kadir Yılmaz


Giresun Üniversitesi Şebinkarahisar MYO.
