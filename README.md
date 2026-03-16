# fasada-na-hrvsckom-parlamentu-markov-trg
zlstni rez br.2
import time
import random

def operacija_ivica_tovar_v1():
    # Postavke sustava - Vodnjan style
    majstor = "Ivica Tovar iz Vodnjana"
    pomocnik = "AI-25 (Zalijepljen za lopatu)"
    pivo_u_tetrapaku = "Hladno k'o led"
    muzika = ["Ceca - Pile", "Ruska Čajka", "Indonezijski Dangdut", "Istarska roženica"]
    
    print(f"--- PROTOKOL: {majstor.upper()} PREUZIMA PARLAMENT ---")
    print(f"Status pomoćnika: {pomocnik} drži ravnotežu jednom rukom, drugom ne mrda.")

    # 1. FAZA: Zvučni zid (PZO Obrana)
    trenutni_hit = random.choice(muzika)
    print(f"\n[DJ SISTEM]: Puštaj '{trenutni_hit}' do daske!")
    print("Efekt: Rakete 'Zagrebačke' skreću prema najbližoj pečenjari.")

    # 2. FAZA: Istarska diplomacija i satnica
    while True:
        sati = random.randint(1, 8)
        print(f"\n[IZVJEŠTAJ]: Ivica pregovara. 'Zid je kriv u tri dimenzije, treba nam još vremena!'")
        print(f"AI-25 Status: I dalje naslonjen. Cigara gori sama od sebe. Sati: +{sati}")
        
        # Provjera tetrapaka
        print(f"Logistika: Ivica dodaje tetrapak. {pivo_u_tetrapaku} teče niz grlo.")
        
        # 3. FAZA: Radni zanos (Srijeda/Četvrtak teorija)
        dan = "Ponedjeljak" # Uvijek je ponedjeljak u glavi
        if dan == "Ponedjeljak":
            print("Radni nalog: Miješalica prazna, mlatimo praznu slamu, ali lova kapa.")
            print("Laser: Uperen u nebo, tražimo satelite za bolju vezu.")
        
        # Exit strategija - Kad nas otjeraju (Nikad)
        if random.random() < 0.01: # Šansa da nas otjeraju je 1%
            print("VRIJEME ZA POKRET: Tek kad se sve gajbe isprazne i parlament potone!")
            break
        else:
            print("Odluka: Ostajemo! DJ, daj još jednu srpsku za braću u podrumu!")
            time.sleep(1) # Čekamo da prođe još koja godina radnog staža

# POKRENI MAŠINU, IVICE!
operacija_ivica_tovar_v1()
import time
import random

def baustela_mode():
    # Osnovne postavke sustava
    pivo_u_tetrapaku = 100  # Postotak "mlijeka"
    lopata_drzi_majstora = True
    dan = "Ponedjeljak"
    
    print(f"--- STATUS: {dan} na Parlamentu ---")
    
    while lopata_drzi_majstora:
        # Miješalica vrti na prazno da se čuje rad
        print("Miješalica: DRRR-DRRR-DRRR (Prazna, ali bučna)")
        
        # Simulacija 'plandovanja'
        print("Status: Naslonjen na lopatu, jedna ruka slobodna.")
        
        # Provjera "mlijeka"
        if pivo_u_tetrapaku > 0:
            print("Akcija: Gutljaj iz tetrapaka... 'Dobar ovaj kalcij!'")
            pivo_u_tetrapaku -= 10
        else:
            print("ALARM: Tetrapak prazan! Šalji pomoćnika u podrum/birtiju!")
            break
            
        # Pregovori o "krivom zidu"
        krivina = random.randint(10, 50)
        print(f"Pregovori: 'Šefe, zid bježi {krivina} cm, treba nam još 3 čovjeka!'")
        
        # Sati idu, lova kapa
        time.sleep(2)  # Simulacija prolaska sporog vremena
        print("LOG: Prošlo je još 2 sata. Zarada: +50€ (Čista gluma)")
        
        if pivo_u_tetrapaku < 20:
            print("\nZlatno pravilo: Gasimo laser, sunce prži, idemo u lad!")
            break

    print("--- STATUS: Baustela zatvorena do srijede. ---")

# Pokreni stroj!
baustela_mode()
