# Projet Météo avec OpenWeatherMap API

Ce projet utilise l'API OpenWeatherMap pour récupérer les données météorologiques de 20 villes françaises. Les données météorologiques sont ensuite stockées dans un DataFrame et exportées au format CSV.

## Prérequis

Pour utiliser ce projet, vous aurez besoin de Python 3.7 ou ultérieur et des bibliothèques suivantes :
- pandas
- requests

Vous pouvez installer ces bibliothèques à l'aide de pip :


```bash 


pip install pandas requests 


```


## Inscription et obtention d'une clé API

Pour utiliser l'API OpenWeatherMap, vous devez vous inscrire et obtenir une clé API. Suivez les étapes ci-dessous pour vous inscrire et obtenir une clé API :

1. Rendez-vous sur le site web d'OpenWeatherMap : https://openweathermap.org/
2. Cliquez sur "Sign Up" en haut à droite de la page pour créer un compte.
3. Une fois inscrit et connecté, cliquez sur "API Keys" dans le menu de navigation en haut.
4. Cliquez sur "Generate" pour générer une nouvelle clé API.
5. Copiez la clé API générée. Vous l'utiliserez dans votre script Python.

## Utilisation

1. Clonez ce dépôt ou téléchargez le fichier .py contenant le code.
2. Ouvrez le fichier .py et remplacez la variable `API_KEY` par la clé API que vous avez obtenue lors de l'inscription à OpenWeatherMap.
3. Exécutez le script Python à l'aide de la commande suivante :

python weather_data.py

4. Le script récupérera les données météorologiques pour les 20 villes françaises et les stockera dans un fichier CSV nommé "weather_data.csv" dans le même répertoire que le script.

## Documentation

Pour plus d'informations sur l'utilisation de l'API OpenWeatherMap, consultez la documentation officielle :

- Documentation de l'API OpenWeatherMap : https://openweathermap.org/api
- Guide de démarrage rapide : https://openweathermap.org/guide

## Licence

Ce projet est distribué sous la licence MIT. Pour plus d'informations, consultez le fichier [LICENSE](LICENSE).
