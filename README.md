## MÁV Utastájékoztató

Ez a projekt egy egyszerű webes felületet biztosít a MÁV vonatindulások és érkezések megjelenítésére. A weboldal **HTML** és **CSS** segítségével készült, és egy táblázatos formátumban jeleníti meg az aktuális menetrendet.

###  Funkciók
-  Induló és érkező vonatok listázása táblázatban
-  Állomás, indulási és érkezési idők megjelenítése
-  Felhasználóbarát, letisztult dizájn

###  Használat
Egyszerűen nyisd meg a  weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.
####  Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[ MÁV Utastájékoztató](https://github.com/Roli0410/2025_01_30_MAV_utastajekoztato.git)

###  Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <table>
        <thead>
        <tr class="elso_oszlop">
            <th>Tervezett érkezés</th>
            <th>Érkezés</th>
            <th>Vonat</th>
            <th>Honnan</th>
            <th>Hova</th>
            <th>Vágány</th>
        </tr>
        </thead>
        <tbody> <tr>
            <td>8:30</td>
            <td>8:42</td>
            <td>IC</td>
            <td>Szeged</td>
            <td>Szatymaz - Kistelek</td>
            <td>5</td>
        </tr>
        </tbody>
         </table>
         </body>
</html>
```

## 🎨 CSS Stílusok
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f8f9fa;
    text-align: center;
}

table {
    width: 80%;
    margin: 20px auto;
    border-collapse: collapse;
}
```

### 🔧 Fejlesztési lehetőségek
- [ ] 🔄 Dinamikus adatbetöltés API-n keresztül
- [ ] 🔍 Keresési és szűrési lehetőségek
- [x] 📱 Reszponzív megjelenítés mobileszközökre