# PyTest Decorators

Python dekoratörlerin görevi;sınıfın veya fonksiyonun işlevini değiştirmektir.
Parametre olarak fonksiyon alır ve geriye fonksiyon döndürür.
Kapsamı istenilen fonksiyonun önüne @ karakteri konulur.

__call__() ==> İstenilen bir nesne çağırılabilir.
@pytest.skip ==> Kendinden sonraki testi atlar.
@pytest.fail ==> Test başarısız olursa,mesaj döndürür.
@pytest.mark.timeout ==> Test verilen sürede tamamlanır.
@pytest.mark.parametrize ==> Testi parametrelendirir.Yani birden fazla girdi gönderilebilir.


