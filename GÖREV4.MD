# Kullanıcıdan bir metin aldık
metin = input("Bir metin girin: ")

# Ters çevrilmiş boş değişkene koydum
tersmetin = ""

# Metni tersten döngüye koydum
for karakter in metin:
    tersmetin = karakter + tersmetin  

# Sonucu ekrana yazdırdım
print("Ters çevrilmiş metin: " , tersmetin)
