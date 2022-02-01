### Step 1 
1. Installiere node.js: 
    > https://nodejs.org/en/download/
2. Überprüfe die Installation (Powershell): 
    > npm -v  
    > node -v

### Step 2 (Alles in bash)
1. Erstelle ein Repository auf GitHub und clone dieses auf deinen PC.
2. Erstelle im Repository-Verzeichnis eine React-App: 
   > npx create-react-app . 
3. Überprüfe die App 
   > npm start
4. Stoppe die App 
   > Strg C
5. . Führe folgende Git commands im Repository-Verzeichnis aus
   > git add . \
   > git commit -m "Add react-app" \
   > git push  

Meldet euch bei mir, sobald ihr so weit seid! 

### Step 3
1. Erstelle im Repository-Verzeichnis folgenden Ordner:
   >mkdir .github/
2. Erstelle im Repository-Verzeichnis folgenden Ordner:
   >mkdir .github/workflows/
3. Erstelle im .github/workflows/ ein file mit der Endung .yml 
4. > touch .github/workflows/pipeline.yml

### Step 4
1. Öffne pipeline.yml
2. Kopiere den zuvor ausgearbeiteten Code in das deployment.yml
3. Push den Code 
   > git add . \
   > git commit -m "Add pipeline" \
   > git push  

Meldet euch bei mir, sobald ihr so weit seid, wir machen gemeinsam weiter!

### Step 5 
1. Aktiviere Github Pages: in den Repository-Einstellungen auf Github
   > Source: Branch: gh-pages
2. Nun solltest du die URL deiner Website sehen -> Ohne Inhalt 

### Step 6
1. Geh in deinen Code in package.json und füge folgendes (Mit deinen Git-Daten) in die Dritte Zeile ein:
   > "homepage": "https://<username>.github.io/<project>/",
2. Push deinen Code, warte bis die Actions durchlaufen sind. Besuche deine Website. 
   > git add . \
   > git commit -m "Add URL" \
   > git push  