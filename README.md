# tp-eslint-git

---

## I - Test de ESLINT

---

```bash
npx eslint app.js
```

![](assets/1.png)

- On remarque que Eslite nous prévient bien de l'erreur

## II - Test de husky

---

```bash
git commit -m "Test du hook ESLint"
```

![](assets/2.png)

- On remarque que husky marche bien
- J'ai modifié le fichier `.huky/pre-commit` pour mettre la bonne commande

### III - modification des configurations en js

- On modifie le `eslint.config.js` pour mettre les configurations du TP 

![](assets/6.png)

- Une fois la conf modifiée, les nouvelles règles sont visibles même sur l'IDE

### IV - Test de github action

---

![](assets/3.png)

- Au début l'action se lance et charge

![](assets/4.png)

- Puis l'action échoue

![](assets/5.png)

- J'ai corrigé le problème afin de pouvoir merge la branch pour ajouter le README a la fin
- Mais du coup j'ai corrigé le problème, et l'action est passée :)

