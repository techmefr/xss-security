# XSS Security Demo

Une démonstration simple et éducative d'une vulnérabilité XSS (Cross-Site Scripting) dans une application web.

## 🚨 Avertissement

Ce projet est strictement à but éducatif. Il démontre une vulnérabilité de sécurité courante afin d'aider les développeurs à comprendre et à prévenir les attaques XSS. Ne jamais utiliser ces techniques sur des sites web sans autorisation explicite.

## 📋 Description

Cette démonstration simule un formulaire web vulnérable aux attaques XSS. Elle montre comment une entrée utilisateur non validée peut être utilisée pour exécuter du code JavaScript non autorisé dans le navigateur d'autres utilisateurs.

## 💡 Comment fonctionne cette vulnérabilité

Dans cette démo, l'entrée utilisateur est insérée directement dans le DOM sans échapper les caractères spéciaux ou effectuer de validation, ce qui permet d'injecter et d'exécuter du code malveillant.

## 🛡️ Comment prévenir les attaques XSS

Pour protéger vos applications contre les attaques XSS, vous devriez :

1. Toujours échapper les caractères spéciaux dans les entrées utilisateur
2. Utiliser des méthodes sécurisées comme `textContent` au lieu de `innerHTML`
3. Mettre en place des Content Security Policies (CSP)
4. Valider les entrées utilisateur côté serveur et côté client
5. Utiliser des frameworks modernes qui échappent automatiquement le contenu

## 🚀 Comment utiliser cette démo

1. Clonez ce dépôt
2. Ouvrez `index.html` dans votre navigateur
3. Essayez d'entrer des balises HTML dans le champ de texte
4. Observez comment le code est exécuté au lieu d'être affiché comme texte

## 📚 Ressources pour en apprendre davantage sur les XSS

- [OWASP Cross-Site Scripting Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- [MDN Web Security](https://developer.mozilla.org/fr/docs/Web/Security)
- [Google Web Fundamentals - Prevent XSS](https://developers.google.com/web/fundamentals/security/prevent-xss)

---

Créé à des fins éducatives dans le cadre d'un apprentissage sur la sécurité web
