# 🎨 Guide – cyber-snippet-smart.css

Ce guide documente les styles disponibles dans le fichier `cyber-snippet-smart.css` pour enrichir tes notes dans Obsidian.

Chaque classe peut être utilisée avec la syntaxe :

```markdown
<span class="nom-classe">Contenu stylisé</span>
```

---

## ✅ Tableau des classes CSS et leur rendu

| Classe CSS        | Usage                                  | Exemple de rendu                   |
|-------------------|-----------------------------------------|------------------------------------|
| concept           | Notions, processus, définitions clés    | <span class="concept">Reconnaissance</span> |
| technology        | Outils, scripts, plateformes            | <span class="technology">Burp Suite</span> |
| protocol          | Protocoles, formats, standards          | <span class="protocol">DNS</span> |
| threat            | Vulnérabilités, attaques, comportements | <span class="threat">XSS</span> |
| indicator         | IOC : IP, hash, user                    | <span class="indicator">192.168.1.1</span> |
| best-practice     | Bonnes pratiques générales              | <span class="best-practice">Activer l’authentification multifactorielle</span> |
| mitigation        | Contremesures techniques ciblées        | <span class="mitigation">Filtrage des entrées côté serveur</span> |
| example           | Commandes, payloads, regex              | <span class="example">nmap -sV -p- target.com</span> |
| goal              | Objectifs de lab ou de phase            | <span class="goal">Obtenir un shell sur la machine cible</span> |
| note              | Notes perso, TODO, tips                 | <span class="note">💡 Penser à tester aussi le paramètre Cookie</span> |

---

## 🛠 Bonnes pratiques d’utilisation

- Utilise les balises **dans des blocs de texte ou des tableaux**
- Ne surcharge pas : limite à 1 ou 2 styles par phrase
- Priorise la **lisibilité** sur la décoration
- Tu peux combiner certaines balises avec du texte Markdown standard

---

## 📦 Intégration

Active le fichier `cyber-snippet-smart.css` via :

```
Obsidian > Paramètres > Apparence > Snippets CSS > Activer
```

📁 Place le fichier dans :
```
Cyber-Brevet-Vault/.obsidian/snippets/
```
