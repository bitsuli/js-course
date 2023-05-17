# Egyszerű HTTP server 

A `http-server` module egy nagyon egyszerű szerver, ami html fájlokat tud kiszolgálni

## Telepítése a következő

```
npm install -g http-server

```

## Készíts HTML fájlt futtasd a szerveredet
1. Ha ez sikerült, hozz létre egy folder `http-server` néven (vagy amilyen nevet szeretnél használni, mindegy)
1. Azon belül hozz létre egy foldert `public` néven (ennek számít a neve)
1. Ebben hozz létre egy fájlt: `index.html`
1. Nyisd meg a fájlt és nyomd meg a `Shift+1`-et
1. Válaszd ki az első felkiáltójelet. Ez elméletileg létrehoz egy üres html fájlt. 
1. Írj bármit a `body` tagek közé, pl. `<h1>Hello</h1>`
1. Mentsd el a fájlt. 
1. Nyisd meg a terminált és lépj be a `http-server` folderbe
1. Futtasd le a parancsot: `http-server`
1. Ha minden jól ment valami ilyesmit kell látnod:
    ```
    Available on:
    http://127.0.0.1:8080
    http://10.0.5.2:8080
    Hit CTRL-C to stop the server

    ```


## Megnyitás böngészőben
Ha a fenti lépéseket Gitpodon csináltad, akkor a bal alsó sarokben kellene látnod egy ilyen feliratot, hogy `Port: 8080`
Kattints rá, majd a megnyíló ablakban kattints a linkre, ami valami ilyesmi: `https://8080-bitsuli-jscourse-uqc5qnh8mwj.ws-eu97.gitpod.io
Ha mindent sikerült összehozni, látnod kell az oldalad tartalát!



