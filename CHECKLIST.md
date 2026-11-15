# Checklist : un PDF est-il lisible par un lecteur d'écran ?

À copier et à cocher. Licence CC BY 4.0.

## Ce qu'un logiciel peut vérifier
- [ ] Du vrai texte (pas une page scannée en image)
- [ ] Un balisage (arbre de structure)
- [ ] La langue déclarée
- [ ] Le titre du document, affiché à la place du nom de fichier
- [ ] Des titres balisés, sans niveau sauté
- [ ] Des images avec un texte de remplacement
- [ ] Des tableaux avec des cellules d'en-tête
- [ ] La norme PDF/UA déclarée dans les métadonnées

## Ce qui demande un humain
- [ ] Le texte de remplacement décrit-il vraiment l'image ?
- [ ] L'ordre de lecture est-il le bon ? (passe au lecteur d'écran : NVDA avec Firefox sous Windows, VoiceOver sous macOS et iOS)
- [ ] Les liens disent-ils où ils mènent ?
