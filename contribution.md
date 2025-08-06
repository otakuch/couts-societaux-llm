# Guide de Contribution

Merci de votre intérêt pour contribuer au projet **Coûts Sociétaux des LLM** ! 🎉

## 📋 Table des matières

- [Code de conduite](#code-de-conduite)
- [Comment contribuer](#comment-contribuer)
- [Signaler un problème](#signaler-un-problème)
- [Proposer une amélioration](#proposer-une-amélioration)
- [Soumettre une Pull Request](#soumettre-une-pull-request)
- [Standards de code](#standards-de-code)
- [Processus de review](#processus-de-review)

## 📜 Code de conduite

En participant à ce projet, vous acceptez de respecter notre [Code de Conduite](CODE_OF_CONDUCT.md). Nous nous engageons à maintenir un environnement accueillant et respectueux pour tous.

## 🤝 Comment contribuer

### 🐛 Signaler un problème

1. **Vérifiez** que le problème n'a pas déjà été signalé dans les [Issues](https://github.com/votre-username/couts-societaux-llm/issues)
2. **Créez** une nouvelle issue en utilisant le template approprié
3. **Décrivez** clairement le problème :
   - Comportement attendu vs observé
   - Étapes pour reproduire
   - Captures d'écran si pertinent
   - Navigateur et OS utilisés

### 💡 Proposer une amélioration

1. **Ouvrez** une issue de type "Amélioration"
2. **Expliquez** :
   - Le problème que votre proposition résout
   - La solution proposée
   - Les alternatives considérées
3. **Attendez** les retours de la communauté avant de coder

### 🔧 Soumettre une Pull Request

#### 1. Préparation

```bash
# Fork le repository
# Clonez votre fork
git clone https://github.com/votre-username/couts-societaux-llm.git

# Ajoutez le repo original comme remote
git remote add upstream https://github.com/original-username/couts-societaux-llm.git

# Créez une branche pour votre fonctionnalité
git checkout -b type/description-courte
```

Types de branches :
- `feature/` - Nouvelle fonctionnalité
- `fix/` - Correction de bug
- `docs/` - Documentation
- `style/` - Changements visuels
- `refactor/` - Refactoring du code

#### 2. Développement

- **Respectez** le style de code existant
- **Testez** vos modifications dans plusieurs navigateurs
- **Documentez** tout nouveau code
- **Mettez à jour** le README si nécessaire

#### 3. Commit

Format des messages de commit :

```
type: description courte (max 50 caractères)

Description détaillée si nécessaire. Expliquez le pourquoi,
pas le comment (le code fait ça).

Résout : #numéro_issue
```

Types de commit :
- `feat:` - Nouvelle fonctionnalité
- `fix:` - Correction de bug
- `docs:` - Documentation
- `style:` - Formatage, CSS
- `refactor:` - Refactoring
- `test:` - Ajout de tests
- `chore:` - Maintenance

#### 4. Soumission

```bash
# Synchronisez avec upstream
git fetch upstream
git rebase upstream/main

# Poussez vers votre fork
git push origin type/description-courte
```

Puis créez une Pull Request via GitHub.

## 📏 Standards de code

### HTML
- Utiliser HTML5 sémantique
- Attributs `alt` pour toutes les images
- Structure accessible (ARIA labels si nécessaire)

### CSS
- Méthodologie BEM pour les classes
- Variables CSS pour les couleurs
- Mobile-first responsive design

### JavaScript
- ES6+ moderne
- Commentaires JSDoc
- Pas de variables globales

### Général
- Indentation : 2 espaces
- UTF-8 encoding
- LF line endings
- Fichiers se terminent par une ligne vide

## 🔍 Processus de review

1. **Review automatique** : Vérification syntaxe et style
2. **Review par les pairs** : Au moins 1 approbation requise
3. **Tests** : Validation multi-navigateurs
4. **Merge** : Par un mainteneur du projet

### Critères d'acceptation

✅ Le code suit les standards du projet
✅ Les tests passent
✅ La documentation est à jour
✅ Pas de régression
✅ Compatible avec les navigateurs supportés

## 📚 Ressources utiles

- [Documentation MDN](https://developer.mozilla.org/fr/)
- [Guide accessibilité](https://www.w3.org/WAI/WCAG21/quickref/)
- [Conventional Commits](https://www.conventionalcommits.org/fr/)

## ❓ Questions ?

- Consultez notre [FAQ](docs/FAQ.md)
- Ouvrez une [Discussion](https://github.com/votre-username/couts-societaux-llm/discussions)
- Contactez les mainteneurs

---

**Merci de contribuer à rendre l'IA plus transparente et responsable ! 🌟**
