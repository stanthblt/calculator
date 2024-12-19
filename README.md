# Construction avec le Dockerfile :

**Exécutez la commande suivante dans le répertoire où se trouve le Dockerfile :**

```bash
docker build . -t calculator
```

## Pour démarrer le conteneur, pensez à exposer les ports en utilisant la commande suivante :

```bash
docker run -p (port):(port) calculator
```

## Pour spécifier vos propres ports, utilisez cette commande :

```bash
docker run -e CALC_PORT=10000 -p 10000:10000 calculator
```

---

# Utilisation de Docker Compose

**Exécutez la commande suivante dans le répertoire contenant le fichier `docker-compose.yml` :**

```bash
docker compose up
```