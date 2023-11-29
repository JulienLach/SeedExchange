## SeedExchange

*Changements à faire sur la branche production*

### Lien live : https://tranquil-kangaroo-7d9bb0.netlify.app/

## Guide

1. Toujours pull avant de travailler en local : 
```
    git pull origin production
    git pull origin main

```

2. Changer de branche :
```
    git branch  // pour voir sur quelle branche on se trouve
    git checkout production // pour changer de branche et aller sur la branche production
```
    
3. On push toujours sur la branche production avant de PR et merge sur la main

4. Rappel ordre des commandes pour push son travail :
```
    git add .
    git status
    git commit -m "message du travail que l'on veut valider"
    git push origin production
```

*Ne jamais push sur la branche main directement*