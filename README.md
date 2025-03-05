# Python Snake Case Converter

Bu proje, **Pascal Case** ve **Camel Case** formatındaki bir metni, **Snake Case** formatına dönüştürmek için yazılmış bir Python kodu içeriyor. Bu proje, **FreeCodeCamp** Python kursu kapsamında geliştirilmiştir.

## Özellikler

- Pascal Case (örneğin: `MyVariableName`) ve Camel Case (örneğin: `myVariableName`) formatındaki metinleri alır.
- Büyük harflerin önüne otomatik olarak alt çizgi (`_`) ekler.
- Sonuçta, metin tüm küçük harflere dönüştürülür ve baştaki/sondaki gereksiz alt çizgiler temizlenir.

## Kullanım

1. Projeyi bilgisayarınıza klonlayın.
   
   ```bash
   git clone https://github.com/FihriSina/python-Snake-Case-Converter.git
   ```

2. Kodu çalıştırın. Örnek kullanım için `main` fonksiyonunu inceleyebilirsiniz.

   ```python
   def main():
       print(convert_to_snake_case('aLongAndComplexString'))

   main()
   ```

   Bu kod, `aLongAndComplexString`'i `a_long_and_complex_string` şeklinde dönüştürecektir.

## Kodun Detayları

1. **convert_to_snake_case**:
   - Pascal Case veya Camel Case formatındaki bir string alır.
   - Büyük harflerin önüne `_` ekler ve stringi küçük harflerle döndürür.
   - Baş ve sondaki `_` karakterlerini temizler.

2. **main**:
   - `main` fonksiyonu, örnek bir string ile `convert_to_snake_case` fonksiyonunu çalıştırır.

## Katkıda Bulunma

Bu proje açık kaynaklıdır. Katkıda bulunmak isterseniz, bir pull request göndererek önerilerinizi paylaşabilirsiniz.
