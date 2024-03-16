# ToDo

Bu proje, Internet Computer Protocol (ICP) üzerinde Motoko programlama dilini kullanarak oluşturulmuş basit bir yapılacaklar listesi akıllı sözleşmesidir. Kullanıcılar, yapılacakları isimlerine göre eklemeler yapabilir, tamamlamalarını işaretleyebilir ve listeden silebilirler.

## Proje Yapısı

Bu projede, `Map`, `Hash`, `Nat`, `Iter` ve `Text` modüllerini kullanarak işlevsel bir yapılacaklar listesi uygulaması oluşturulmuştur.

## Tanımlanan Veri Tipi

`ToDo`: Bir yapılacak görevin tanımlanması için kullanılmıştır. Bu veri tipi, bir görevin açıklamasını ve tamamlanma durumunu içerir.

## Kullanılan Modüller ve Fonksiyonlar

- **HashMap Modülü:** Görev isimlerini karşılık gelen bilgileriyle eşleyen değiştirilebilir bir koleksiyon oluşturmak için kullanılır.
- **Hash Modülü:** Metin verilerini hashlemek için kullanılır.
- **Nat Modülü:** Doğal sayılarla çalışmak için kullanılır.
- **Iter Modülü:** Döngü ve iterasyon işlemleri için kullanılır.
- **Text Modülü:** Metin verileriyle çalışmak için kullanılır.

## Akıllı Sözleşme İşlevleri

- **getTodos():** Tüm yapılacak görevlerin listesini almak için kullanılır.
- **addTodo(description):** Yeni bir yapılacak görev eklemek için kullanılır.
- **completeTodo(id):** Belirli bir yapılacak görevi tamamlanmış olarak işaretlemek için kullanılır.
- **showTodos():** Tüm yapılacak görevleri göstermek için kullanılır.
- **clearCompleted():** Tamamlanmış olan tüm görevleri temizlemek için kullanılır.

## Nasıl Kullanılır?

1. Akıllı sözleşmeyi başlatmak için gerekli olan modülleri içe aktarın.
2. Yapılacaklar listesi için bir HashMap oluşturun.
3. İstenirse yapılacak görevleri ekleyin, işaretleyin veya temizleyin.

## Katkı

Motoko Akıllı Sözleşme Yapılacaklar Listesi projesine katkıda bulunmak isterseniz, bu depoyu çatallayabilir, değişikliklerinizi yapabilir ve bir pull request gönderebilirsiniz.