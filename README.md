# goruntu-isleme-yesil-fon-renk-ayirma


S uzayı için 150 eşik değerinin altındaki pikseller siyah, üstündeki pikseller ise beyaza 
dönüştürüldü. 
Ardından elde edilen H ve S uzayına ait görüntüler çarpılarak birbirlerine karşılık gelen 
siyah ve beyaz pikseller birbirini götürdü. 
“bwareopen” metodu ile 150’den daha az sayıda yan yana gelen pikseller görmezden 
gelinerek karartıldı. RGB çarpımları yapılarak maskelenmiş görüntü elde edildi.
