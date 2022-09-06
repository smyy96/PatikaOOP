# Patika OOP

```
Patika platformundaki OOP ödevleri

• Üniversite Yönetim Sistemi
• Hayvanat Bahçesi Yönetimi

```
[Ders İçeriği](https://app.patika.dev/courses/oop)

### Encapsulation (Kapsülleme)
```
Sarmalama ilkesi, bir sınıfa ait değişkenlerin veya niteliklerin ancak o sınıfa
ait metotlar tarafından değiştirilebilmesi ve okunabilmesi ilkesidir. Bu ilke 
sayesinde nesnelerde oluşacak anlamsızlıkların önüne geçilebilir.
```

### Inheritance (Kalıtım)
```
Kalıtım Türleri
• Tek Yönlü Kalıtım (Single Inheritance)
    Bir sınıfın başka bir sınıfı genişlettiği alt ve ata sınıf ilişkisini ifade eder.
    A → B
    
• Çoklu Kalıtım (Multiple Inheritance)
    Bir sınıfın birden fazla sınıfı miras almasını ifade eder; bu, bir alt sınıfın iki
    ata sınıfa sahip olduğu anlamına gelir.
    A → B
    ↓
    C
    
• Çok Seviyeli Kalıtım (Multilevel Inheritance)
    Bir sınıfa ait alt sınıfın başka sınıfları genişletmesine denir.
    A → B → C

• Hiyerarşik Kalıtım (Hierarchical Inheritance)
    Birden fazla sınıfın aynı sınıfı genişlettiği bir alt ve üst sınıf ilişkisini 
    ifade eder.
    B
    ↑
    A → C
    ↓
    D
    
• Hibrit Kalıtım (Hybrid Inheritance)
    Programda birden fazla kalıtım türünün kombinasyonuna denir. 
    
    A → B 
    ↓   ↓
    C → D
    
```

### Polymorphism (Çok Biçimlilik)
```
Polimorfizm, alt sınıfların ata sınıflardaki metotları geçersiz kılması(method overriding)
sayesinde çok biçimli olarak davranmasına denir. Bu sayede alt sınıf ata sınıfından 
gelen davranışı kendine göre şekillendirebilir.

Metotlarda "Geçersiz Kılma" ise bir alt sınıfın içine doğrudan ya da dolaylı ata sınıflarından
gelen bir(ya da daha fazla) yöntemin aynısının(aynı yöntem adı ve aynı parametre listesi) 
kodlanmasına verilen addır.

```

### Abstraction (Soyutlama)
```
Nesne yönelimli programlamada Soyutlama (Abstraction) ilkesi, eğer bir sınıf için nesne
üretmek mantıksız geliyorsa o sınıf soyutlanabilir. 
Soyutlama kavramı sınıfın içindeki iç işleyişi dışarıdan izole etmek, yani gizlemektir.

Soyutlama için Java'da iki yöntem mevcuttur:
    • "interface" tanımlamak
    • "abstract" sınıf tanımlamak
    
Soyut Sınıf Özellikleri:

"abstract" anahtar kelimesi ile tanımlanmış olması gerekiyor.
    • Soyut veya soyut olmayan fonksiyonlar tanımlanabilir.
    • Soyut sınıflardan "new" anahtar kelimesi ile nesne oluşturulamaz.
    • Kurucu metodu ve static fonksiyonlar tanımlanabilir.
    • "final" kelimesi ile tanımlanmış fonksiyonları içerebilir. Bu final fonksiyonlar 
      alt sınıflarda ezilemezler (override).
```















