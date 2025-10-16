HNET Complete Deployment
===================

Ce pack contient :
- Backend Node.js/Express complet avec Moov & MTN Benin
- Frontend simple (Register/Login/Dashboard/Retrait)
- Dockerfile + docker-compose pour déploiement rapide
- .env.example pour tes clés Moov, MTN et JWT_SECRET

Instructions de déploiement rapide :
1. Copier `.env.example` en `.env` et remplir tes clés
2. Installer Docker sur ta machine ou VPS
3. Dans le dossier du projet : 
   docker-compose up -d --build
4. Accéder au site sur http://localhost:3000/ (ou ton IP publique si VPS)

Déploiement public :
- Utilise Render, Railway, ou VPS avec redirection des ports + HTTPS
