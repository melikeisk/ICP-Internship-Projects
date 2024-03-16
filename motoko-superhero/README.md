# Superheroes Akıllı Sözleşmesi

Bu akıllı sözleşme, Motoko dilinde yazılmış bir süper kahraman yönetim uygulamasıdır. Kullanıcılar, süper kahramanları oluşturabilir, okuyabilir, güncelleyebilir ve silebilirler.

## Veri Yapıları

- `SuperheroId`: Süper kahraman kimlik numarasını temsil eder.
- `Superhero`: Süper kahramanın adını ve sahip olduğu süper güçleri içerir.

## Fonksiyonlar

- `create(superhero: Superhero): async SuperheroId`: Yeni bir süper kahraman oluşturur ve kimlik numarasını döndürür.
- `read(superheroId: SuperheroId): async ?Superhero`: Belirli bir süper kahramanın bilgilerini alır.
- `update(superheroId: SuperheroId, superhero: Superhero): async Bool`: Belirli bir süper kahramanı günceller.
- `delete(superheroId: SuperheroId): async Bool`: Belirli bir süper kahramanı siler.

## Kullanılan Modüller

- `List`: Liste veri yapısı için kullanılır.
- `Option`: Opsiyonel değerler üzerinde işlem yapmak için kullanılır.
- `Trie`: Anahtar-değer çiftlerini depolamak ve yönetmek için kullanılır.
- `Nat32`: Doğal sayılarla çalışmak için kullanılır.

## Nasıl Kullanılır

1. Akıllı sözleşmeyi başlatmak için gerekli modülleri içe aktarın.
2. Süper kahramanlar için bir trie veri yapısı oluşturun.
3. İstenirse süper kahramanlar ekleyin, güncelleyin veya silin.

## Katkı

Bu projeye katkıda bulunmak için, bu depoyu çatallayabilir, değişikliklerinizi yapabilir ve bir pull request gönderebilirsiniz.
