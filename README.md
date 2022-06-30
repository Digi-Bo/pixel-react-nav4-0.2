# Gestion du Header dans react navigation

on définit le style de chaque routes

## Dans le dossier routes/HomeStackNav.js

```javascript
const screens = {
  Home: {
    screen: Home,
    navigationOptions: {
      title: "Accueil",
      headerStyle: { backgroundColor: Colors.blueColor },
    },
  },
  Portfolio: {
    screen: Portfolio,
    navigationOptions: {
      title: "Profil",
      headerStyle: { backgroundColor: Colors.blueColor },
    },
  },
  Photo: {
    screen: Photo,
    navigationOptions: {
      title: "Photos",
      headerStyle: { backgroundColor: Colors.blueColor },
    },
  },
};
```
