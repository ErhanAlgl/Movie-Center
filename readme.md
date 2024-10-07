# Film İzleme Uygulaması

Bu proje, The Movie Database (TMDb) API'sini kullanarak kullanıcıların film detaylarını görmesine ve film kategorilerini keşfetmesine olanak sağlayan basit bir web uygulamasıdır. Kullanıcılar, kategorilere göre filmleri keşfedebilir, her filmin detaylarını görebilir ve favori listelerine ekleyebilir.

## Ekran Kaydı
https://github.com/user-attachments/assets/64620433-1e29-4f18-95e8-4fea56be9ba6

## Özellikler

- **Kategoriler Menüsü**: Filmler, türlerine göre kategorilere ayrılmıştır. Kategoriler TMDb API'den dinamik olarak yüklenir.
- **Popüler Filmler**: Site yüklendiğinde varsayılan olarak popüler filmler listelenir.
- **Film Detayları**: Bir filme tıklayarak filmin başlık, puan, kategori ve açıklama gibi detaylarını görebilirsiniz.
- **Favoriler**: Kullanıcılar, filmleri favori listesine ekleyebilir ve favori filmlerini ayrı bir sayfada görebilir.

## Sayfalar

### 1. Ana Sayfa (`index.html`)
Popüler filmlerin ve kategoriler menüsünün görüntülendiği sayfa. Bir kategori seçildiğinde, o kategoriye ait filmler gösterilir.

### 2. Film Detayları Sayfası (`product.html`)
Seçilen bir filme ait detayların gösterildiği sayfa. Kullanıcı, filmi favorilere ekleyebilir.

### 3. Favoriler Sayfası (`favorites.html`)
Kullanıcının favori listesine eklediği filmlerin görüntülendiği sayfa. Filmlere tıklayarak detay sayfasına gidebilirsiniz.

## Favori Filmler

Favori filmler tarayıcınızın `localStorage`'ında saklanır. Bir filmi favorilere eklediğinizde, sayfa yenilendikten veya tarayıcı kapatıldıktan sonra bile favorileriniz korunur.

## Kullanılan Teknolojiler

- **HTML**: Sayfa yapısını oluşturmak için.
- **CSS**: Kullanıcı arayüzünü stilize etmek için.
- **JavaScript**: Dinamik etkileşimler, API çağrıları ve DOM manipülasyonu için.
- **TMDb API**: Film verilerini almak için.
- **Bootstrap**: Responsive tasarım ve hazır UI bileşenleri için.

## API Hakkında

1. **TMDb API Anahtarını Alın**:
   Bu projeyi kullanabilmek için ücretsiz bir TMDb hesabı oluşturmalı ve bir API anahtarı edinmelisiniz. API anahtarınızı [TMDb API belgeleri](https://www.themoviedb.org/documentation/api) sayfasından alabilirsiniz.

