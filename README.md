# BMI2



الوزن= float(input('ادخل وزنك بالكيلوجرام'))
الطول= float(input('ادخل طولك بالامتار '))



BMI =(2 **الطول) /الوزن

if BMI < 18.5:
  print("شديد النحافة")

elif 18.5 <= BMI < 25:
    print("طبيعي")

elif 25 <=BMI < 50:
    print("سمنة")

else:
    print("سمنه مفرطه")



print(f"مؤشر كتلة الجسم {BMI:2f}")

