# 💰 zWorth – DonutSMP-Like Worth Plugin

zWorth ist ein Minecraft Spigot Plugin, das wie das "Worth-System" von DonutSMP funktioniert.  
Es zeigt den aktuellen Marktwert von Items direkt im Inventar an – dynamisch, live und automatisch.

## ⚙️ Features

- 📦 **Item-Wert-Anzeige** im Lore jedes Items
- 🧠 **Automatische Preisaktualisierung** bei jeder Bewegung & alle 0.5 Sekunden
- 🔁 Stackt auch Items mit **unterschiedlicher Lore**
- 💸 Zeigt **Gesamtwert** + **Preis pro Einheit**
- 🚫 **Dupe-sicher** & stack-limitiert auf 64
- 🔄 **Live-Reload** über Befehl `/worthreload`
- 🔄 **Worth GUI** über Befehl `/wort`

---

## 📁 Beispiel `config.yml`

```yaml
items:
  DIAMOND:
    price-per-unit: 250.0
  NETHERITE_INGOT:
    price-per-unit: 1000.0
  DIRT:
    price-per-unit: 0.1
```

---

## 🧪 Beispiel Lore im Spiel

```text
§7Preis: §a1250.00$ §7(§a250.00§7/Stk)
```

(Bei 5 Diamanten im Stack)

---

## 🔧 Befehle

| Befehl           | Beschreibung                      | Permission        |
|------------------|-----------------------------------|-------------------|
| `/worthreload`   | Lädt die Plugin-Konfiguration neu | `zworth.reload`   |
| `/worth`         | OPEN WORTH GUI                    | `non`   |



---

## 📦 Installation

```bash
# 1. Plugin herunterladen
# 2. In den plugins/ Ordner deines Spigot-/Paper-Servers legen
# 3. Server starten
# 4. config.yml anpassen
# 5. Mit /worthreload live neuladen
```

---

## 🧠 Inspiration

Dieses Plugin ist inspiriert vom **Worth-System auf DonutSMP**,  
das die wirtschaftliche Bedeutung von Items in PvP & Survival spürbar macht.

---

## ✅ To-Do / Ideen

```text
[ ] GUI-Shop mit Verkaufspreisen  

[ ] /sell Command zum Itemverkauf  
[ ] Top-Worth Rangliste  
[ ] Stats je Spieler (gesamt verkauft etc.)  
[ ] Unterstützung für Custom Items  
```

![Screenshot 2025-04-10 100007](https://github.com/user-attachments/assets/4791a4b4-dcea-4f05-8e86-7d204eda07b0)
![Screenshot 2025-04-10 095940](https://github.com/user-attachments/assets/1e56f849-2f43-4595-8c58-a7632dbb65af)
