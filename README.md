# Riješene LV iz predmeta Sjiwp.
Ovdje se nalaze sve laboratorijske vježbe iz predmeta Sjiwp, riješene na točan način (vjerojatno jesu, ali ne mogu to garantirati).

Na web stranici https://karlo-sjiwp.netlify.com možeš vidjeti sve LV u akciji, i na početnoj stranici možeš skinuti arhiv riješene vježbe.

# Kako doprinositi projektu:
- Forkaj projekt na GitHub-u
- Kloniraj svoj forkan projekt na svoje računalo (pomoću Git-a u komandnoj liniji ili Git integraciji u VS Code-u):
	- `git clone git@github.com:TvojeKorisničkoIme/Sjiwp.git` ili
	- `git clone https://github.com/TvojeKorisničkoIme/Sjiwp.git`
- Napravi novi branch (za ime brancha koristi nešto što opisuje što ćeš napraviti, npr: "IspravakLV02"):
	- `git checkout -b ImeBrancha`
- Commit-aj i push-aj svoje promijene redovito:
	- `git add .` (`.` stage-a (priprema) sve promijenjene datoteke, zamijeni ju s imenima datoteka koje želiš commitati)
	- `git commit -m "Poruka koja opisuje promijene u tom jednom commitu"` (commita sve stage-ane datoteke u lokalni repozitorij)
	- `git push` (šalje sve commitove, koji još nisu pushani, na GitHub repozitorij)
- Kada si gotov, kreiraj Pull Request od svojeg repozitorija na master branch ovog repozitorija
