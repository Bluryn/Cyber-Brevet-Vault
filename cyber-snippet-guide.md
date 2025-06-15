# 🧵 Guide d'utilisation – `cyber-snippet.css`

Ce fichier CSS est destiné au vault **Cyber-Brevet-Vault** pour formater visuellement des éléments clés de cybersécurité.

## 🔠 Classes disponibles

| Classe CSS        | Usage prévu                                        |
|-------------------|---------------------------------------------------|
| `concept`         | Définition, processus, méthodologie               |
| `technology`      | Outils, scripts, plateformes                      |
| `protocol`        | Protocoles, formats de logs, standards réseau     |
| `threat`          | Vulnérabilités, attaques, comportements suspects |
| `indicator`       | IOCs : IP, hash, username, artefact               |
| `best-practice`   | Bonnes pratiques générales                        |
| `mitigation`      | Contremesures techniques spécifiques              |
| `example`         | Commandes, regex, payloads, code                  |
| `goal`            | Objectifs de lab ou scénario                      |
| `note`            | Annotation personnelle (⚠️, 💡, 📌…)              |

---

## 🧪 Exemples

```markdown
<span class="concept">Reconnaissance</span> utilise <span class="technology">theHarvester</span> pour extraire des emails via <span class="protocol">DNS</span>.

<span class="threat">SQLi</span> peut exposer des données sensibles.

<span class="indicator">Hash suspect : f2d4a1e8b03aa1f3eac9f...</span>

<span class="best-practice">Limiter les droits d'accès aux bases sensibles</span>

<span class="mitigation">Configurer une règle YARA pour bloquer mimikatz</span>

<span class="example">Commande : sqlmap -r login.req --dump</span>

<span class="goal">But : obtenir un accès administrateur à l'application</span>

<span class="note">💡 Penser à vérifier aussi les logs DNS dans Zeek</span>
```

---

📌 Active ce CSS uniquement dans **Cyber-Brevet-Vault** :  
Place-le dans `.obsidian/snippets/` et active-le via `Paramètres > Apparence > Snippets CSS`.
