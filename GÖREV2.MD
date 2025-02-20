# Kullanıcıdan bir sayı aldım
sayi = int(input("Bir sayı girin: "))

# Toplam 0 dan başlattım
toplam = 0

# 1 de itibaren yazılan sayıları topladık
for i in range(1, sayi + 1):
    toplam += i

# Sonucu ekrana verdim 
print("yazılan sayıların toplamı" , toplam)
