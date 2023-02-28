# Notes

So notes for how things work in this repo:
- Aims:
  - main file: `demo.tex`
  - makes heavy use of the latex vscode extension
- Committee:
  - Faculty Search:
    - notebook to scrape faculty bios & build a committee
  - faculty_to_info.pkl
    - saved pickle of scraped faculty bios (to not DDOS the servers)


save env:
- build env:
  - `mamba create --name prelims --file spec-file.txt`
- wsl (ubuntu)
  - `mamba list --explicit > spec-file.txt`