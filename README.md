#Ro'yxatdan nusxa olish
#Bir ro'yxatdan ikkinchi ro'yxatni list2=list1 tarzida hosil qilib bo'lmaydi. Chunki list2 list1 ga yo'lanma (sikl) bo'lib qoladi. 
#Ro'yxatdan nusxa olish uchun copy() funksiyasi ishlatiladi
meva1= ["olma", "banan", "apelsin", "nok", "uzum"]
meva2=meva1.copy()
print(meva2)

#Ro'yxatdan nusxa olishning boshqa usuli
meva2=list(meva1)
print(meva2)
