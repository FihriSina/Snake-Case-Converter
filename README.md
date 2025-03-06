# Snake Case Converter

This project contains Python code designed to convert a text in **Pascal Case** and **Camel Case** formats into **Snake Case** format. This project was developed as part of the **FreeCodeCamp** Python course.

## Features

- Accepts text in **Pascal Case** (e.g., `MyVariableName`) and **Camel Case** (e.g., `myVariableName`) formats.
- Automatically adds an underscore (`_`) before uppercase letters.
- Converts the text to all lowercase letters, removing any unnecessary leading or trailing underscores.

## Usage

1. Clone the project to your computer:
   
   ```bash
   git clone https://github.com/FihriSina/python-Snake-Case-Converter.git
   ```

2. Run the code. You can check the `main` function for an example usage:

   ```python
   def main():
       print(convert_to_snake_case('aLongAndComplexString'))

   main()
   ```

   This code will convert `aLongAndComplexString` to `a_long_and_complex_string`.

## Code Details

1. **convert_to_snake_case**:
   - Takes a string in Pascal Case or Camel Case format.
   - Adds an underscore before uppercase letters and returns the string in lowercase.
   - Removes any leading or trailing underscores.

2. **main**:
   - The `main` function runs the `convert_to_snake_case` function with an example string.

## Contributing

This project is open source. If you would like to contribute, feel free to submit a pull request with your suggestions.



# Snake Case Dönüştürücü

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
