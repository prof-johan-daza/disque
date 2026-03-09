# GitHub

## 1. Terminal MAC – Disque

```python title="TerminalMAC.py" linenums="1" hl_lines="1"
diskutil list
```

## 2. Terminal MAC – Mot de passe PDF

```python title="TerminalMAC.py" linenums="1" hl_lines="1"
cd ~/Downloads
qpdf --password=TU_CLAVE --decrypt "archivo_entrada.pdf" "archivo_sin_clave.pdf"
```

## 3. Terminal VISUAL – Clone GitHub

```python title="TerminalVISUAL.py" linenums="1" hl_lines="1"
git remote add origin https://github.com/prof-johan-daza/disque.git
git clone https://github.com/prof-johan-daza/general.git
```

## 4. Terminal VISUAL – Commitetpush

```python title="TerminalVISUAL.py" linenums="1" hl_lines="1"
cd "/Users/johandaza/Documents/Documents - MacBook Air de Johan/disque"
ou cd "/Users/johandaza/Documents/Documents - MacBook Air de Johan/general"
git init
git add .
git commit -m "NombredelCommit"
git push origin main
```

## 5. Terminal MAC – Arrêt de terminal

```python title="TerminalMAC.py" linenums="1" hl_lines="1"
^C
```

## 6. Terminal VISUAL – Mettre à jour mon local depuis le distant

```python title="TerminalMAC.py" linenums="1"
git stash push -u -m "pre-rebase: DS_Store" && git rebase origin/main && git push origin main
```

## 7. Terminal VISUAL – Format

```python title="TerminalVisual.py" linenums="1"
!!! abstract ""
    Colonnes de notes affichées dans Pronote :

    → "Nombre de la feuille" feuille – "Thématique dans la progresssion" – Feuille élève  
    ["Nombre de la feuille" – Cliquez ici pour télécharger les documents - Auteur : "Nom auteur"](https://prof-johan-daza.github.io/general/"Classe"/"S+#semaine Dossier"/"S+#semaine.pdf")  
    → "Nombre de la feuille" feuille – "Thématique dans la progresssion" – Corrigé  
    ["Nombre de la feuille" – Cliquez ici pour télécharger les documents - Auteur : "Nom auteur"](https://prof-johan-daza.github.io/general/"Classe"/"S+#semaine Dossier"/"S+#semaine+C.pdf")
```

## 8. Terminal VISUAL – Ouvrir exactement ce dossier dans VS Code

```python title="TerminalVISUAL.py" linenums="1"
code .
```
