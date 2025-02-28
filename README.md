# 🔓 UnlockerFXAP - Tuto d'Installation

> **Avertissement :** Ce décryptage est uniquement destiné à débloquer le côté serveur.

---

## 🚨 **Prérequis**
Avant de commencer l'installation, vous devez disposer de l'asset sur votre **CLÉ KEYMASTER**.  
Par exemple, pour débloquer le `LB PHONE`, vous devez déjà l'avoir dans votre **CLÉ KEYMASTER**.

---

## 📥 **1) Installation du Décrypteur**
1. **Téléchargez le décryptage** :  
   [Télécharger UnlockFiveM.rar](https://github.com/loeve1337/)

2. **Mot de passe du `.zip`** :  
   Le mot de passe pour extraire le fichier est : `escrowdecrypterbyloeve`

3. **Extraire les fichiers** :  
   Une fois le fichier `.rar` téléchargé, extrayez les fichiers sur votre bureau.

---

## ⚙️ **2) Configuration des fichiers**
1. Déplacez le dossier `turboh` à la racine de votre disque système (`C:\`).
   - Exemple : `C:\turboh`

   ![Exemple](https://i.postimg.cc/L43L5yq3/image.png)

2. Modifiez la **clé Keymaster** dans le fichier `UnlockFiveM/cfx/server.cfg` à **Ligne 12**.
   
3. Configurez le fichier `config.json` en ajoutant l'ID des rôles, etc.

4. Modifiez l'emplacement du bot dans `src/commands/cfx.js` à la **Ligne 190**.  
   ⚠️ **Remplacez chaque `\` par `\\` dans les chemins !**

---

## 📦 **3) Installation des prérequis**
1. **Installez Java** et **NodeJS** :
   - [Télécharger Java](https://www.java.com/fr/download/)
   - [Télécharger NodeJS](https://nodejs.org/fr)

2. **Activer les intents sur votre bot** :  
   ![Exemple](https://i.postimg.cc/Mp30QYTn/image.png)

---

## ✨ **4) Personnalisation et lancement**
1. Modifiez les messages dans `src/commands/cfx.js`.  
   **Tous les messages commencent par** `interaction.reply`.

2. Exécutez `start.bat` pour démarrer le décryptage.

---

## 🛠️ **🚨 Problème avec `wmic` ?**

Si `wmic` n’est pas installé, suivez ces étapes :

👉 [Guide Microsoft](https://techcommunity.microsoft.com/blog/windows-itpro-blog/how-to-install-wmic-feature-on-demand-on-windows-11/4189530)

### Étapes :
1. Ouvrez **Paramètres Windows**.
2. Allez dans **Système**.
3. Cliquez sur **Fonctionnalités facultatives**.
4. En haut à droite, cliquez sur **"Afficher les fonctionnalités"**.
5. Recherchez **WMIC**.
6. Cliquez sur **Installer**.
7. Relancez `start.bat`.

---

⚠️ **Note :** Ce décryptage ne fonctionne que pour le côté serveur.  
Profitez-en bien et **restez prudent** ! 🔐

---

🔗 **Liens Utiles :**
- [Discord](https://discord.gg/astralisrp)  
- [GitHub](https://github.com/loeve1337/)
