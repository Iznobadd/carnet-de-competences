# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ✔️
- les spécifités du mot-clef `this` ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

```javascript
class Knight {
    constructor(hp = 0, atk = 0, def = 0, skills = []) { // Initialisation des propriétés par défaut
        // Création et initialisation des propriétés de la classe Knight
        this.hp = hp;
        this.atk = atk;
        this.def = def;
        this.skills = skills;
    }


    bio() {
        return `BIO => HP : ${this.hp}, ATK : ${this.atk}, DEF: ${this.def}, Skills : ${this.skills}`
    }
    addSkill(name) {
        const newSkill = [...this.skills, name]; // Utilisation du spread pour récuperer le tableau des skills et y ajouter une valeur
        this.skills = newSkill;
        return "New skill added";
    }
}

const knight1 = new Knight(); // Création d'une instance de la classe Knight
knight1.addSkill("Skill 1"); // Ajout de skills
knight1.addSkill("Skill 2");
knight1.bio(); // Affichage
```

### Utilisation dans un projet ❌

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Pattern JS

- [lien](https://archive.org/details/learning-patterns/learning-patterns-final-v1.1/mode/2up)
- Livre gratuit en ligne qui explique le design pattern et le component pattern pour créer une app avec JS vanilla et React

### Asynchronisme

- [lien](https://www.youtube.com/watch?v=05mKXSdkCJg)
- Vidéo qui explique comment fonctionne l'asynchronisme avec JS

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌
- J'ai fait une [présentation](...) ❌

