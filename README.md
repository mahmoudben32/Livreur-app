# amorce-technique-back-end-planificateur-app

# Mobilis-plateform

Access the live application here:  
👉 [Mobilis Platform](https://main-bvxea6i-jenwo4in7lt44.fr-3.platformsh.site/)

## 🔐 Authentification

### Planificateur (Claudia Tessier)
- **Email:** ctr@mobilis.fr
- **Mot de passe:** 147258

### Livreur (Malik Kepler)
- **Email:** mkr@mobilis.fr
- **Mot de passe:** 123456

------

## 🚀 Lancer l'application en local

### 1. Avec Docker Compose

```bash
docker compose -f docker/docker-compose-local.yml up --detach
cd backend
mvn clean install
mvn spring-boot:run -f server
```
