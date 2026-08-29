# Zermelo api bruno

[English](readme.en.md) | **Nederlands**

Dit is een repository die de Zermelo API in Bruno zet voor testen en als naslagwerk voor **jouw** projecten.

## Hoe te gebruiken

1. Download het project: code -> Download Zip
2. Pak het uit met je favoriete uitpakprogramma
3. Klik in Bruno op het hamburgermenu rechtsboven
4. File -> Open Collection
5. Selecteer de uitgepakte map
6. Configureer de omgevingsvariabelen door in de navigatie van Bruno op `zermelo` te klikken -> `1 collection environment` en stel in ieder geval de variabelen `baseUrl` en `code` of `access_token` in

## Mapstructuur

``` yaml
zermelo-api-bruno
├── documented # Endpoints gedocumenteerd op https://docs.zportal.nl/docs/
├── enviroments
│   └── zermelo.yaml # Configuratie voor variabelen
├── undocumented # Endpoints die niet gedocumenteerd zijn op https://docs.zportal.nl/docs/
└── readme.md # Dit bestand

```

## Todo

- [x] endpoints uit de [docs](https://docs.zportal.nl/docs/)
- [ ] endpoints uit de [swagger ui](https://rlo.zportal.nl/static/swagger/)

## Bijdragen

Als je wilt bijdragen, doe dat vooral. Het makkelijke gedeelte is net gedaan en we moeten nog het grootste deel van de API documenteren.

### Tools
https://rlo.zportal.nl/static/swagger/

https://docs.zportal.nl/docs/

### Richtlijnen

- Geen nependpoints - alle endpoints moeten terug te vinden zijn in de [swagger ui](https://rlo.zportal.nl/static/swagger/)
- Geen locatie-specifieke endpoints. Ik heb deze nog niet gevonden, maar mocht je ze wel vinden - maak **geen** pull request aan met deze endpoints.