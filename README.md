# nlw03-happy Omnistack

Workshop Rockseat NextLevelWeek 03 (2020-10-12) - Trilha OmniStack (Avançado)

## Layout Proposto

> <https://www.notion.so/Layout-Happy-OmniStack-faac4d4d638343fe8bab627125a7557c> (Créditos RocketSeat)

---

## Fontes

Utilizadas fontes customizadas pelo Google Fonts <https://fonts.google.com>

* Nunito
  * 600 Semi-bold
  * 700 bold
  * 800 extra-bold

  ```html
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@600;700;800&display=swap" rel="stylesheet">
  ```


## Bibliotecas necessárias

* react-icons

  ```bash
  yarn add react-icons
  ```

* react-router-dom <https://reactrouter.com/web/guides/quick-start>

  ```bash
  yarn add react-router-dom
  yarn add @types/react-router-dom -D
  ```

* Mapas
  * <https://leafletjs.com/>
  * <https://react-leaflet.js.org/>
  
  ```bash
  yarn add leaflet react-leaflet
  yarn add @types/react-leaflet -D
  ```

  * Existem dois mapas free para utilizar:
    * <https://www.openstreetmap.org>
    * <https://www.mapbox.org> => Para este mapa é necessário cadastro prévio. Após cadastro:
      * copiar o token da API
      * criar um arquivo .env na raiz do App (./web) contendo

      ```bash
      REACT_APP_MAPBOX_TOKEN=<<SEU_TOKEN_VAI_AQUI>>
      ```

      * Reiniciar a App

---

## Linguagens

* React
* NodeJS
* TypeScript
