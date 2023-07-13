# Seattle Rust User Group presentations
Slides in this repository may generated using Common Markdown syntax (`.md`).

To render them:
1. install `marp-cli` using your package manager.
1b) On OSX, `brew install marp-cli` did not place `marp` in my path.  I used `ln -s /usr/local/Cellar/marp-cli/3.1.0/bin/marp <folder in search path>/marp` to fix this.
2. Ensure either Google Chrome or Microsoft Edge is installed on your platform (`marp` dependency)
3. `marp --pdf --allow-local-files /2023.01` # or whichever folder (or `.md` file) you wish to process.
4. Enjoy the output!
