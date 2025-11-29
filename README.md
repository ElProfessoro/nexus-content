# NEXUS Content Repository

Stockage des articles scientifiques multilingues pour NEXUS.

## 📁 Structure

- `/articles/` - Articles en Markdown (fr, en, es, de)
  - `/fr/` - Articles en français
  - `/en/` - Articles en anglais
  - `/es/` - Articles en espagnol
  - `/de/` - Articles en allemand
- `/authors/` - Fichiers JSON des auteurs
- `/public/images/` - Métadonnées images (hébergées sur Cloudinary)

## 🤖 Automatisation

Articles générés automatiquement via N8N + Gemini API et poussés vers ce repo.

## 📝 Format des articles

Voir `/articles/fr/_template.md` pour le format standard.

## 🎨 Thèmes et couleurs

- Science: #2196F3 (bleu)
- Médecine: #F44336 (rouge)
- Technologie: #9C27B0 (violet)
- Environnement: #4CAF50 (vert)
- Espace: #FF9800 (orange)
- Société: #FFEB3B (jaune)
