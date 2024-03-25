# Token

Bu dosya, ICRC1 Ledger Transfer Actor'ünü içerir. Bu aktör, tokenlerin hesaplar arasında transferini sağlar.

## Veri Türleri

- **Account**: Hesapların sahibini ve alt hesap bilgisini içerir.
- **TransferArgs**: Token transferi için gerekli argümanları içerir.

## Fonksiyonlar

- **transfer**: Token transferini gerçekleştiren asenkron bir işlevdir.

## Kullanılan Modüller

- `Icrc1Ledger`: ICRC1 Ledger canister'ına erişim sağlar.
- `Debug`: Hata ayıklama işlevlerini sağlar.
- `Result`: İşlem sonuçlarını işler.
- `Option`: Opsiyonel değerleri işler.
- `Blob`: Binary büyük nesneleri işler.
- `Error`: Hata türlerini işler.
- `Nat8`: 8-bit doğal sayıları işler.

## Nasıl Kullanılır?

1. Dosyayı projenize dahil edin.
2. `transfer` fonksiyonunu kullanarak token transferi gerçekleştirin.
3. Transfer işlem sonuçlarını kontrol edin ve gerekirse işlemi yönetin.

## Katkılar

- Eğer katkıda bulunmak istiyorsanız, bu depoyu çatallayabilir ve değişikliklerinizi yapabilirsiniz. Bir pull request göndermekten çekinmeyin.
