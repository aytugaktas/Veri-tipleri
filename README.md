# MySQL Veri Tipleri

Veritabanı sistemlerinde, farklı türde verileri saklamak için çeşitli veri tipleri kullanılır. MySQL de bu amaçla geniş bir veri tipi yelpazesi sunar. Bu dokümantasyonda, MySQL'in temel veri tipleri ve bunların kullanımı hakkında detaylı bilgiler bulunmaktadır.

## 1. Sayısal Veri Tipleri:
Sayısal değerleri hafızada tutmaya yarayan veri türleridir. Nümerik veri türü olarak da adlandırılırlar. 3 temel nümerik veri tipi vardır. Bunlar; tamsayı, ondalık sayı ve binary sayı veri tipleridir.

### 1.1. TINYINT
- Boyut: 1 byte
- Aralık: -128 ile 127 (signed), 0 ile 255 (unsigned)
- Kullanım: Küçük tamsayıları temsil etmek için kullanılır.

### 1.2. SMALLINT
- Boyut: 2 byte
- Aralık: -32768 ile 32767 (signed), 0 ile 65535 (unsigned)
- Kullanım: Orta büyüklükteki tamsayıları temsil etmek için kullanılır.
  
### 1.3. INT veya INTEGER
- Boyut: 4 byte
- Aralık: -2147483648 ile 2147483647 (signed), 0 ile 4294967295 (unsigned)
- Kullanım: Genel amaçlı tamsayıları temsil etmek için kullanılır.

### 1.4. BIGINT
- Boyut: 8 byte
- Aralık: -9223372036854775808 ile 9223372036854775807 (signed), 0 ile 18446744073709551615 (unsigned)
- Kullanım: Büyük tamsayıları temsil etmek için kullanılır.

### 1.5. DECIMAL veya NUMERIC
- Boyut: Değişken
- Kullanım: Sabit noktalı sayıları temsil etmek için kullanılır. Örneğin, DECIMAL(5,2) 5 basamaklı, 2 ondalık basamaklı bir sayıyı temsil eder.

## 2. Metinsel Veri Tipleri:
MySQL'de kullanılan temel metinsel veri tipleri şunlardır:

### 2.1. CHAR
- Boyut: Belirli
- Kullanım: Sabit uzunluktaki metinleri temsil etmek için kullanılır. Örneğin, CHAR(10) maksimum 10 karakter uzunluğunda bir metni temsil eder.

### 2.2. VARCHAR
- Boyut: Belirli
- Kullanım: Değişken uzunluktaki metinleri temsil etmek için kullanılır. Örneğin, VARCHAR(255) maksimum 255 karakter uzunluğunda bir metni temsil eder.

### 2.3. TEXT
- Boyut: Değişken
- Kullanım: Uzun metinleri temsil etmek için kullanılır.

## 3. Tarih ve Zaman Veri Tipleri:
MySQL'de kullanılan temel tarih ve zaman veri tipleri şunlardır:

### 3.1. DATE
- Format: 'YYYY-MM-DD'
- Kullanım: Yalnızca saati temsil etmek için kullanılır.

### 3.2. TIME
- Format: 'HH:MM:SS'
- Kullanım: Yalnızca saati temsil etmek için kullanılır.

### 3.3. DATETIME
- Format: 'YYYY-MM-DD HH:MM:SS'
- Kullanım: Tarih ve saati birlikte temsil etmek için kullanılır.

### 3.4. TIMESTAMP
- Boyut: 4 byte
- Kullanım: Zaman damgası olarak kullanılır. Örneğin, bir kayıt oluşturuluğunda veya güncellendiğinde otomatik olarak güncellenir.

  
