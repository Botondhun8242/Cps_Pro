# ⚡ CPS PRO v6.2 - Global Edition 🐍
### **Developed by Piton Studio** 🇭🇺

A **CPS PRO** egy nagy pontosságú, professzionális kattintási sebességmérő (CPS) és tesztkörnyezet játékosoknak. Ez a verzió már tartalmazza a teljes kontrollertámogatást, a csalás elleni védelmet és a többnyelvű kezelőfelületet.

---

## 🚀 Főbb Jellemzők

* **🔥 Adaptive Fire Mode:** 12 CPS felett az interfész "tűz üzemmódba" vált dinamikus vizuális effektekkel.
* **🎮 Controller Support:** Beépített Xbox/PlayStation kiosztás teszteléshez. Mérd le a kontrollered válaszidejét!
* **⌨️ Anti-Cheat KPS:** Speciális billentyű-leütés figyelő, amely figyelmen kívül hagyja a nyomva tartott gombokat.
* **🌍 Multi-Language:** 6 nyelv támogatása (Magyar, Angol, Német, Francia, Orosz, Kínai).
* **🔒 Secure Login:** Beépített felhasználói rendszer SQLite adatbázissal és "Maradj belépve" (1 hetes munkamenet) opcióval.
* **📊 Statisztikák:** Az utolsó 10 eredményedet automatikusan menti és megjeleníti az előzményeknél.
* **🌓 Dark & Light Mode:** Választható sötét és világos téma a kényelmes használat érdekében.

---

## 🛠 Technikai specifikációk

* **Nyelv:** Python 3.x
* **GUI:** Tkinter (Egyedi Piton Studio dizájnnal)
* **Adatbázis:** SQLite3
* **Biztonság:** SHA-256 jelszó titkosítás
* **Kompatibilitás:** Windows (EXE-ként is), Linux, macOS, Android (Pydroid 3-mal)

---

## 💻 Telepítés és futtatás

1.  **Python telepítése:** Győződj meg róla, hogy a [Python](https://www.python.org/) telepítve van.
2.  **Futtatás:**
    ```bash
    python Cps_pro_V6.py
    ```

### Hogyan készíts belőle EXE fájlt?
Ha saját alkalmazást szeretnél gyártani belőle, használd a PyInstallert:
```bash
pip install pyinstaller
pyinstaller --onefile --windowed --name=Cps_Pro --icon="icon.ico" Cps_pro_V6.py
```
---
© 2026 Piton Studio. Minden jog fenntartva.
