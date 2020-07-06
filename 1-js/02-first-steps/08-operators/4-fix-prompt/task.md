importance: 5

---

<<<<<<< HEAD
# Corrigez l'addition

Voici un code qui demande à l'utilisateur deux nombres et montre leur somme.

Cela ne fonctionne pas correctement. La sortie dans l'exemple ci-dessous est `12` (pour les valeurs d'invite par défaut).

Pourquoi ? Réparez-le. Le résultat doit être `3`.
=======
# Fix the addition

Here's a code that asks the user for two numbers and shows their sum.

It works incorrectly. The output in the example below is `12` (for default prompt values).

Why? Fix it. The result should be `3`.
>>>>>>> 445bda39806050acd96f87166a7c97533a0c67e9

```js run
let a = prompt("First number?", 1);
let b = prompt("Second number?", 2);

alert(a + b); // 12
```