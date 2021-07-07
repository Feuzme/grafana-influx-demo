# Lancement projet Grafana

## Lancer Grafana

``` Shell
docker-compose up grafana
```
1. http://localhost:8093/
2. admin/admin

## Installer les modules nodes

npx permet d'executer des commandes nodes qui ne sont pas "globales"

```
npm i -g npx
```

## lancer un projet react TS
se placer dans un répertoire et taper :
```
npx create-react-app app-ts-1 --typescript
```
Attention, votre version de node doit être >10.0

## Créer un plugin
```
npx @grafana/toolkit plugin:create mon-plugin
```