# 👾 Space Invaders

Jednostavna browser igra inspirisana klasičnim **Space Invaders** naslovom, napravljena u čistom **HTML + JavaScript**.  
Igrač kontroliše svemirski brod koji se kreće levo i desno i puca na neprijatelje koji dolaze odozgo.

---

## 🕹️ Opis

Cilj igre je jednostavan — uništi sve neprijatelje pre nego što oni stignu do tebe.  
Igra koristi osnovnu game loop logiku, detekciju kolizije i manipulaciju DOM-a / canvas-a za renderovanje pokreta i metaka.  

---

## 📂 Struktura projekta
      ├── images/ – slike (player, enemy, pozadina)
      ├── sounds/ – zvuci (pucanj, eksplozija, itd.)
      ├── index.html – glavna HTML stranica igre
      ├── index.js – ulazna tačka aplikacije
      ├── Player.js – klasa za igrača
      ├── Enemy.js – klasa za neprijatelje
      ├── Bullet.js – klasa za metke
      ├── EnemyController.js – kontrola neprijatelja
      ├── BulletController.js – kontrola metaka
      └── MovingDirection.js – pomoćna klasa/enumeracija za pravce


---

## 🚀 Kako pokrenuti

1. Kloniraj repozitorij:
   ```bash
   **git clone https://github.com/ndjerma/space-invaders.git**
   
2. Otvori fajl index.html u svom browseru (dvostruki klik je dovoljan).

3. Koristi ← → strelice za kretanje i Space za pucanje.

4. Uništi sve neprijatelje i pokušaj da preživiš što duže!
