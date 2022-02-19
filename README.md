# theo_berget

hp=float(input('Quelle est la hauteur le la prèmiere couche(mm)'))
hbp=float(input("quelle est la distance entre la buse et le plateau?(mm)"))
result=round((hp-hbp)*0.7,1)

if result<0 : 
  s='antihoraire'
  
else :
 s='horaire'

print(abs(result), "tours dans le sens", s)
