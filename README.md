🌌 Stargazer – Aplicație web cu tematică spațială
Stargazer este o aplicație web construită cu React, dedicată iubitorilor de astronomie care doresc să exploreze universul într-un mod interactiv și vizual. Aplicația permite utilizatorilor să vizualizeze imagini NASA zilnice, să descopere informații cosmice interesante și să salveze imagini favorite pentru a reveni la ele oricând.

🧩 Funcționalități implementate
Pagină principală cu banner video și tematică cosmică

Routing complet între paginile aplicației folosind react-router-dom

Apelare API NASA (Astronomy Picture of the Day)

Salvare și vizualizare favorite – imaginile și videoclipurile pot fi salvate și accesate într-un popup elegant

Popup pentru favorite cu design adaptat pentru desktop și mobil (versiune dragabilă pe telefon)

Responsive Design – aplicația se adaptează automat la dispozitiv

Management de stare prin Context API + useReducer (pentru favorite)

Design unitar cu temă întunecată (spațială), culori cosmice și fonturi clare

🚧 În lucru
Următoarele pagini sunt incluse în aplicație, dar nu sunt încă funcționale. Ele vor fi completate ulterior:

🪐 Calendar – urmează să includă evenimente astronomice

🛰️ Sky Today – va afișa cerul în timp real, poate cu localizare

💫 Facts – va conține curiozități despre univers și sistemul solar

🔧 Tehnologii utilizate
React

React Router DOM

Context API + useReducer

HTML5, CSS3, JavaScript ES6+

NASA Public API

Create React App (CRA)

Git & GitHub

🗂️ Structura generală
pgsql
Copiază codul
📁 public/
    ├── index.html
    └── assets/banner.mp4

📁 src/
    ├── assets/
    ├── components/
    ├── context/
    ├── pages/
    ├── styles/
    ├── App.js
    └── index.js
▶️ Instrucțiuni de rulare locală
Clonează repository-ul:

bash
Copiază codul
git clone https://github.com/alina-idk/stargazer.git
Navighează în directorul proiectului:

bash
Copiază codul
cd stargazer
Instalează toate dependențele:

bash
Copiază codul
npm install
Rulează aplicația local:

bash
Copiază codul
npm start
Aplicația va fi disponibilă la http://localhost:3000.

🙋‍♀️ Autor
Proiect realizat de Alina, ca parte a unui proiect individual.
