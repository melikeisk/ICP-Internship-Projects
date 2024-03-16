# Colculator

Bu akıllı sözleşme, temel hesap makinesi işlevlerini gerçekleştiren bir aktördür. Toplama, çıkarma, çarpma, bölme ve temizleme gibi işlemleri destekler.

## Değişkenler

- `hucre`: Hesap makinesinin mevcut değerini tutar. İşlemler bu değişken üzerinde gerçekleşir.

## Operatörler

- `toplama(s: Int)`: Mevcut değeri `s` ile toplar.
- `cikarma(s: Int)`: Mevcut değerden `s`'yi çıkarır.
- `carpma(s: Int)`: Mevcut değeri `s` ile çarpar.
- `bolme(s: Int)`: Mevcut değeri `s`'ye böler. Eğer `s` sıfırsa, null döner.
- `temizle()`: Hesap makinesinin mevcut değerini sıfırlar.

## Async Metodu

Her işlev, sonucu asenkron olarak döndürür. Bu sayede işlemler paralel olarak gerçekleştirilebilir ve aynı anda birden fazla işlem başlatılabilir.

## If Condition

Bölme işlemi sırasında, sıfıra bölme hatası kontrol edilir. Eğer bölen sıfırsa, null dönülür ve hatanın önüne geçilir.

## Nasıl Kullanılır?

1. Akıllı sözleşmeyi başlatmak için gerekli modülleri içe aktarın.
2. İstenilen işlemi çağırarak hesap makinesi işlevlerini kullanın.
3. Temizleme işlemi için `temizle()` işlevini çağırarak hesap makinesinin mevcut değerini sıfırlayın.

## Katkı

Bu projeye katkıda bulunmak için, bu depoyu çatallayabilir, değişikliklerinizi yapabilir ve bir pull request gönderebilirsiniz.