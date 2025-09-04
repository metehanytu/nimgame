# Nim

Bu proje, klasik **Nim oyununu** görsel bir arayüzle oynamanıza olanak tanır. Arayüz ve temel oyun mekaniği ChatGPT tarafından oluşturulmuştur.

## Kurallar
- Oyun, 4 satırda sırasıyla **1, 3, 5 ve 7 kibrit çöpü** ile başlar.
- Oyuncular sırayla hamle yapar.
- Bir hamlede, **sadece bir satırdan** en az 1 kibrit çöpü alınabilir.
- Hamle yapma hakkı bitene kadar (yani satır boşalana kadar) aynı satırdan almaya devam edilir.
- **Son kibriti alan oyuncu kaybeder** (misère Nim kuralı).

## Kontroller
- **-1 al**: Seçilen satırdan bir kibrit eksiltir.
- **PC move**: Bilgisayara hamle yaptırır.
- **Bilgisayar Düşüncesi**: Bilgisayarın yaptığı hesaplamaları gösteren paneli açar/kapatır.
- **Yeni Oyun**: Oyun tahtasını başlangıç konumuna sıfırlar.

## Notlar
Bu proje, eğitsel amaçla Nim stratejilerini anlamak ve denemek için oluşturulmuştur. Bilgisayarın hamle algoritması dilediğiniz gibi değiştirilebilir; varsayılan fonksiyon örnek olarak bırakılmıştır.
