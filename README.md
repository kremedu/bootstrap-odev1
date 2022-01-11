# bootstrap-odev-1
patika.dev / kodluyoruz.org Bootstrap eğitiminin 1. ödevi 

## Istenilenler

css-odev1 deki sayfanın bootstrap kullanılarak yeniden tasarlanması
- HTML kısmını önceki ödevden alabilirsiniz fakat baştan yapmanızı öneririz.
- Menüyü koyu renkli olarak düzenleyin. İsterseniz arka plan rengi de verebilirsiniz.
- Ana sayfaya bir jumbotron koyup içeriğinizin açıklamasını yazınız.
- Arka plan rengini #E9ECEF ile değiştirin.
- Ürünlerimiz sayfasında card yapısını kullanın.
- Kullandığınız card yapısını grid sistemin içinde kullanın.
- Ürün card boyutlarının tamamen aynı olduğuna dikkat edin.
- Hakkımızda sayfasını da bir card yapısı içine alın.
# Sonuç
![resim](img/sonuc.png)

## Bilinen Sorunlar
- CÖZÜLDÜ (canvas tagi, z-index) "products.html" sayfasında container'ın particle.js arkaplanın üzerinde konumlanması ve responsive özelliği korumak için position: fixed; kullanılıyor (absolute kullanılınca çözünürlük değiştiğinde sistem yapıyı eski haline alamıyor) ve bu sebepten dolayı sayfada scroll yapılamıyor. 
- card öğelerinde yazıların bulundugu grid/col genişliğinin veya card öğelerinde bulunan yazıların uzunluğuna göre card boyutu değişmemeli.   
