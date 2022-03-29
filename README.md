# code_Media
print("Calculando sua média")
N = int(input("Quantas provas? : "))
total_temp = 0

for n in range (N):
    PNP = float(input("pontuação na prova"))
    total_temp += PNP

media = total_temp / N

print("Sua média é: ",media)
