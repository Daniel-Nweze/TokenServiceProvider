# 🛡️ TokenServiceProvider

Detta är ett delsystem som ansvarar för att generera och validera JWT-tokens. Det är ett fristående backend-API som är publicerat live via Render, och kan användas av resten av gruppens projekt.

## 📌 Funktioner

### `POST /api/Auth/token`
Skapar en JWT-token baserat på:
- `userId` (obligatorisk)
- `email` (valfri)
- `role` (valfri)

### `POST /api/ValidateToken`
Validerar att en token är:
- giltig
- signerad korrekt
- innehåller samma `userId` som skickats in

---

## 🔧 Användning

*https://tokenserviceprovider.onrender.com*

---

## 📊 Diagram
Sekvensdiagram – Tokenvalidering
![image](https://github.com/user-attachments/assets/f708bc24-a912-475b-8d6e-f54ee5cf09e0)

📄 Aktivitetsdiagram – Tokenvalidering
![image](https://github.com/user-attachments/assets/de5a8b32-a5d3-40a5-9dcd-7c13aea10974)
