# Bu çalışma diğer dünya ülkelerinde indsanların türkiyeyi na kadar ercih etmiş.

## Burda üç adımda Model kurdum burda yapılan işlemler sırasıyla:
    1. Bir ülke seçip ondan sonra onun üzerinden zaman serilerinde çalışmaya dayalı model kurma.
    2. Burda istenilen ülkeyi seçip ondan sonra tahmin yapmaya dayalı bir model kurup çalışma.
    3. Burda ise açılan dünya haritası üzerinden interaktif bir şekilde seçmeyi sağlayan ve yine hepsi olduğu gibi zaman serilerinde çalışan bir model.

## Kullanılan model olarak ise ARIMA kullanıyorum burda LSTM tercih etmeme sebebim veri seti ve veri seti daha az zaman indexli veri az daha fazla veride LSTM daha başarılı olur.

## Bu çalışma nasıl ve ne için kullanılabilir.
- Çalışmanın amacı turizim sektöründe hangi ülkenin insanını ülkemizi tatil destinasyonu olarak tercih ediyormu.
- Ülkelelerden gelen turis durumuma göre o ülkelerin reklam ve kanpanya planlaması için çalışmna yapılması.
- Yine turizimde arz ve talep durumuna göre fiyat belirlejnmede fiyatı lokaleştirmede kullanıla bilir.

## Kullanılan kütüpaneler:

- pandas (pd): Veri işleme ve analizi için kullanılan bir kütüphanedir. Veri çerçeveleri ve seriler ile veri manipülasyonu ve analizini kolaylaştırır.

- matplotlib.pyplot (plt): Veri görselleştirmesi için kullanılan bir kütüphanedir. Grafikler, çizelgeler ve diğer görselleştirme araçlarını oluşturmak için kullanılır.

- statsmodels.tsa.arima.model (ARIMA): Zaman serisi analizi için kullanılan bir modeldir. ARIMA (AutoRegressive Integrated Moving Average) modeli, zaman serilerinin tahmin edilmesinde kullanılır.

- warnings: Uyarıları kontrol etmek ve bastırmak için kullanılan bir Python modülüdür. warnings.filterwarnings('ignore') ile uyarılar gizlenir.

- numpy (np): Matematiksel ve sayısal hesaplamalar için kullanılan bir kütüphanedir. Özellikle büyük veri dizileri ve matrisler ile çalışmak için kullanılır.

- plotly.express (px): Etkileşimli veri görselleştirmeleri oluşturmak için kullanılan bir kütüphanedir. Grafikler ve çizelgeler oluşturmak için basit bir API sunar.

- plotly.graph_objs (go): Plotly'nin daha ayrıntılı ve özelleştirilebilir görselleştirme araçlarını sağlayan bir kütüphanedir. Grafiklerin daha detaylı yapılandırılmasını sağlar.

- dash: Web tabanlı veri görselleştirme ve kullanıcı arayüzleri oluşturmak için kullanılan bir framework'tür. Dash uygulamaları, etkileşimli web uygulamaları oluşturmak için kullanılır.

- dash.Dash: Dash uygulaması oluşturmak için kullanılan sınıftır.
  
- dash.dcc: Dash'ın etkileşimli bileşenlerini içeren modüldür. Örneğin, grafikler ve slider'lar içerir.
  
- dash.html: HTML bileşenleri ve layout'lar oluşturmak için kullanılan modüldür.
  
- pycountry: Ülke isimleri, kodları ve diğer ülke bilgilerini sağlayan bir kütüphanedir. Ülke bilgilerini almak ve düzenlemek için kullanılır.

  
## Katkıda Bulunma
Katkıda bulunmak isterseniz lütfen bir pull request açın veya bir issue oluşturun.

## Lisans
Bu proje Licanse dosyası ile lisans ile lisanslanmıştır.
