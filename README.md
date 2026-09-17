mkdir -p /home/claude
cat > /home/claude/README.md << 'EOF'
# Global Alucovit Construction — Site vitrine

Site web vitrine de **Global Alucovit Construction**, entreprise spécialisée dans la menuiserie aluminium, le verre et les façades vitrées à Douala, Cameroun.

🔗 **Site en ligne :** https://lekingatonfact-bit.github.io/

## À propos

Global Alucovit Construction propose des services de :
- Menuiserie aluminium et verre
- Pose de baies vitrées et façades vitrées
- Faux plafonds
- Portes et fenêtres
- Vitrines commerciales
- Rampes d'escalier, cloisons et miroiterie

## Structure du site

```
.
├── index.html       # Page d'accueil
├── services.html    # Détail des services proposés
└── README.md
```

## Contact

- **Téléphone :** +237 678 385 097 / +237 697 452 535
- **Email :** alexgabind@gmail.com
- **Adresse :** Pk10, Douala, Cameroun
- **Horaires :** Lundi – Samedi, 9h – 19h

## Hébergement

Le site est hébergé gratuitement via **GitHub Pages**.

## Notes techniques

- Site statique en HTML/CSS/JS, sans framework.
- Les demandes de devis se font via des liens `mailto:` qui ouvrent directement l'application email du visiteur avec un message pré-rempli.
- ⚠ Ce site ne doit **pas** contenir de scripts ou de liens spécifiques à Cloudflare (`/cdn-cgi/...`), car il n'est pas hébergé derrière Cloudflare. Ces artefacts (protection anti-robot, obfuscation d'email) causent des liens cassés et des écrans de chargement infinis sur mobile.

## Mise à jour du site

Pour modifier le contenu, éditer directement `index.html` ou `services.html` puis pousser les changements sur la branche principale du dépôt — GitHub Pages republie automatiquement le site après chaque commit.
EOF
cp /home/claude/README.md /mnt/user-data/outputs/README.md
