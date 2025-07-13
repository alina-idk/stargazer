# Stargazer Web App 🌌✨

Stargazer este o aplicație web tematică dedicată explorării cosmosului, realizată cu React, HTML5 și CSS3. Proiectul oferă o experiență captivantă de descoperire a imaginilor și informațiilor din univers, într-un design modern, responsive și ușor de utilizat.

## 🚀 Funcționalități principale

- 🏠 **Pagina principală (Home):** Banner video tematic, buton Explore și galerie NASA.  
- 🌐 **Rutare dinamică:** Navigare între pagini cu React Router Dom.  
- 💾 **Managementul stării:** Favorite salvate folosind Context API, cu popup pentru vizualizare și gestiune.  
- 🛰️ **Apelare API NASA:** Imagini și videoclipuri oficiale din spațiu.  
- 📱 **Design responsive:** Meniu hamburger pe mobil și navbar pe desktop.  
- 🎨 **Temă vizuală personalizată:** Gradient albastru-negru și font Comfortaa.

## 🚧 În lucru

Următoarele pagini sunt incluse în aplicație, dar nu sunt încă funcționale. Ele vor fi completate ulterior:

- 🪐 **Calendar** – urmează să includă evenimente astronomice  
- 🛰️ **Sky Today** – va afișa cerul în timp real, poate cu localizare  
- 💫 **Facts** – va conține curiozități despre univers și sistemul solar

## 🎨 Elemente de design personal

Logo-ul aplicației, bannerul video de pe pagina principală și imaginile din pagina 404 au fost create personal în Canva. Acestea conferă o notă personală și unitară întregii aplicații, reflectând implicarea creativă dincolo de cod.

## 🛠️ Tehnologii utilizate

- React  
- React Router DOM  
- Context API + useReducer  
- HTML5, CSS3, JavaScript ES6+  
- NASA Public API ([https://api.nasa.gov/](https://api.nasa.gov/))  
- Create React App (CRA)  
- Git & GitHub  

## ⚙️ Cum să rulezi proiectul local

Clonează repository-ul pe calculatorul tău:

```

git clone https://github.com/alina-idk/stargazer.git
```
Intră în folderul proiectului:

Copiază codul
```


cd stargazer
```
Creează un fișier .env pornind de la .env.example:

Pe Windows, în Command Prompt (CMD) sau PowerShell:

Copiază codul

```


copy .env.example .env
```
Pe Mac/Linux în terminal:


Copiază codul
```
cp .env.example .env
```
Editează fișierul .env pentru a adăuga cheia ta API NASA:

Deschide .env în editorul tău preferat și modifică linia astfel:

env

Copiază codul
```
REACT_APP_API_KEY=your_nasa_api_key_here
```
Dacă nu ai o cheie API, o poți obține gratuit de pe https://api.nasa.gov/.

Instalează toate pachetele necesare:



Copiază codul
```
npm install
```
Pornește serverul de dezvoltare local:



Copiază codul
```
npm start
```
Deschide aplicația în browser:

Accesează în browser adresa:



Copiază codul
```
http://localhost:3000
```
⚠️ Notă importantă
Fișierul .env nu este inclus în repository pentru securitate.

În schimb, în repo există .env.example ca să știi ce variabile să configurezi.

Folderul node_modules nu este inclus pe GitHub, pentru că poate fi generat local cu npm install.

🙏 Mulțumiri și feedback
Acest proiect este o lucrare individuală, creată cu pasiune pentru cosmos și tehnologie. Feedback-ul constructiv este binevenit pentru îmbunătățiri viitoare!
