# **_GitHub_**
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
cd ~/Documents/disque # cd ~/Documents/disque ou cd ~/Documents/general
git init
git add .
git commit -m "NombredelCommit"
git push origin main
```