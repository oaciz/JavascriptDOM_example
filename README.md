* Kod, basit bir görev listesi uygulaması oluşturur.
* HTML dosyasında bir form, bir metin girişi, iki düğme ve bir liste bulunmaktadır.
* JavaScript dosyası, belirli bir görevin eklenmesini, seçilmesini ve silinmesini sağlayan işlevler içerir.
* loadItems() fonksiyonu, sayfa yüklendiğinde localStorage'dan önceki görev listesini alır ve ekrana yükler.
* getItemsFromLS() fonksiyonu, localStorage'dan görev listesini alır. Eğer kayıt yoksa, boş bir dizi oluşturur.
* setItemToLS(newTodo) fonksiyonu, yeni bir görevi localStorage'a ekler.
* createItem(newTodo) fonksiyonu, belirli bir görevi HTML'de listeye ekler.
* addNewItem(e) fonksiyonu, form gönderildiğinde yeni bir görev ekler ve localStorage'a kaydeder.
* deleteItem(e) fonksiyonu, silme düğmesine tıklandığında bir görevi listeden ve localStorage'dan siler.
* deleteTodoFromStorrage(deletetodo) fonksiyonu, belirli bir görevi localStorage'dan siler.
* deleteAllItems(e) fonksiyonu, tüm görevleri listeden ve localStorage'dan siler.
