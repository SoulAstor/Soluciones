# Soluciones

#Suma de N

print(sum(int(digito) for digito in input().strip()))

#Ola Ivan

estado = input().strip()

if estado == "conectado":
    print("Ola Ivan")
else:
    print("Ol..")

#Dos gatos y un Raton
A, B, C = map(int, input().strip().split())

distancia_gato_A = abs(A - C)
distancia_gato_B = abs(B - C)

if distancia_gato_A < distancia_gato_B:
    print("gato A")
elif distancia_gato_B < distancia_gato_A:
    print("gato B")
else:
    print("raton C")
