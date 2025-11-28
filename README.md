# 📄 **README.md — Mini Site Docker + Nginx**

```markdown
# Mini Site Web avec Docker, Nginx et Docker Compose

Ce projet est un site web statique (HTML/CSS/JS) servi par un conteneur **Nginx**.  
Il utilise un volume bind pour permettre la mise à jour du site **en temps réel** sans reconstruire l'image.

## 🚀 Fonctionnalités

- Serveur web Nginx dans un conteneur Docker
- Volume bind : modifications instantanées du HTML
- Orchestration avec Docker Compose
- Mapping du port 8080 → 80
- Projet simple pour apprendre les bases du DevOps

## 📁 Structure du projet

```

mini-docker-site/
│── index.html
│── docker-compose.yml
└── README.md

```

## 🐳 Lancement avec Docker Compose

Assurez-vous d'être dans le dossier du projet :

```

docker compose up -d

```

Voir les conteneurs :

```

docker compose ps

```

Arrêter le projet :

```

docker compose down

```

## 🌐 Accès au site

Une fois lancé, ouvrez dans votre navigateur :

👉 http://localhost:8080

Toute modification dans `index.html` est visible immédiatement grâce au volume.

## 🛠 Technologies utilisées

- Docker
- Docker Compose
- Nginx (image `nginx:alpine`)
- HTML/CSS/JS

## 🎯 Objectif pédagogique

Ce mini-projet fait partie de mon parcours d’apprentissage DevOps :

- maîtriser Docker
- comprendre les volumes
- piloter un service avec Docker Compose
- préparer le terrain pour un pipeline CI/CD
```

---