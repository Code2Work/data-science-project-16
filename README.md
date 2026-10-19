# Data Science Python Project 16 — Betimsel İstatistik (Ortalama, Medyan, Mod, Std)

### Proje Kurulumu
Projeyi öncelikle forklayın ve clone edin.
Proje sayımız ilerledikçe proje yönetimimizi kolaylaştırmak adına projelerimizi belli klasör kalıplarında saklamak iyi bir alışkanlıktır.
Örnek bir Lokasyon: Code2Work/DataScience/data-project-16.

### Proje Kurulumu Komutlar
Aşağıdaki komutları sırasıyla çalıştırınız.
* `python -m venv venv`
* `venv\Scripts\activate` (Windows) — macOS / Linux için: `source venv/bin/activate`
* `pip install -r requirements.txt` => Tüm bağımlılıkları kurar
* `python watch.py` => Kaydettikçe testleri otomatik çalıştırır ve **skorunu Kaizu'ya gönderir**
* `python tests/test_question.py` => Testleri tek seferlik çalıştırır ve **skorunu Kaizu'ya gönderir**

> ⚠️ **Başlamadan önce:** `tests/test_question.py` dosyasının başındaki `USER_ID = 0` satırına **kendi Kaizu ID'ni** yaz (Profile → Settings → User ID). Yazmazsan skorun gönderilmez.

## Bonus
* Eğer daha detaylı bir şekilde testlerin içerisine bakmak isterseniz:
* `pytest tests/test_question.py -s -v` (sadece testleri gösterir, **skor göndermez**)

### Projeye Başlamadan Önce
* Bu bir **Python** projesidir. Veritabanı kurulumuna, SQL sorgusuna ya da herhangi bir bağlantı ayarına **gerek yoktur**.
* Çalışırken sadece `tasks/task_manager.py` dosyasında çalışacağız. Bu dosyanın dışındaki kodları değiştirmeyiniz!
* Her fonksiyonun ne yapması gerektiği `tasks/task_manager.py` içindeki yorum satırlarında açıklanmıştır. Fonksiyonların içini doldurunuz.
* Testleri çalıştırarak doğru sonuç alıp almadığınızı adım adım kontrol edebilirsiniz.

# Questions
* Senaryo:
    Hogwarts'ta öğrencilerin sınav notları ve ev (house) puanları üzerinde çalışacaksın.
    Ortalama, medyan, mod, standart sapma, persentil, çeyrekler ve aykırı değer (outlier) hesaplarını yapacak;
    hangi merkezi eğilim ölçüsünün veriye uygun olduğuna karar veren bir kural yazacaksın.
* `tasks/task_manager.py` dosyasının içerisindeki fonksiyonların içerisini doldurmaya çalışın.
