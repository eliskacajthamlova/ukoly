# ukoly
# ukol1
jmeno = input("zadejte svoje jmeno:")
vek = input("zadejte svuj vek:")
print(f"Ahoj, jmenuji se {jmeno} a je mi {vek} let.")


#ukol2
cislo1 = float(input("zadej prvni desetine cislo:"))
cislo2 = float(input("zadej druhe desetine cislo:"))

soucet = cislo1 + cislo2
rozdil = cislo1 - cislo2
soucin = cislo1 * cislo2
if cislo2 != 0:
    podil = cislo1 / cislo2
else:
    podil = None

print(f"Soucet: {soucet:.2f}")
print(f"Rozdil: {rozdil:.2f}")
print(f"Soucin: {soucin:.2f}")
if podil is not None:
    print(f"Podil: {podil:.2f}")
else:
    print("podil nelze vypocitat (deleni nulou).")
