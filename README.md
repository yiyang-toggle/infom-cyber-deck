# INFOM Cybersecurity Deck

Toggle's cybersecurity growth deck for INFOM, served with GitHub Pages:
https://yiyang-toggle.github.io/infom-cyber-deck/ (repo: yiyang-toggle/infom-cyber-deck; move to toggle-workspace when an org owner can create it)

`index.html` is a build output and holds the whole deck (fonts and styles included). Do not edit it here.
The source lives in toggle-brain at `clients/infom/deck/`. To update:

```
cd toggle-brain/clients/infom/deck
python3 build.py --client ../../../../infom-cyber-deck
```

Then commit and push this repo. Pages redeploys in about a minute.
