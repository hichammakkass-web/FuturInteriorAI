cat > README.md << 'EOF'
# 🏠 FuturInteriorAI

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## ✨ Transformez vos photos en designs d'intérieur futuristes avec IA

**FuturInteriorAI** est une application Python complète qui transforme vos photos de locaux en designs d'intérieur futuristes professionnels avec vidéos, listes d'achats et devis.

### 🎯 Fonctionnalités Principales

- 📸 **Reconstruction 3D** à partir de photos via LumaAI
- 🎨 **Styles IA** tendances mis à jour quotidiennement (Stable Diffusion)
- 🎬 **Vidéos professionnelles** avec Blender + voix off ElevenLabs
- 🗣️ **Musique générative** avec Suno AI
- 🛒 **Shopping list automatisée** avec prix et fournisseurs
- 💰 **Devis multi-devises** avec taxes par pays
- 📱 **Interface moderne** avec CustomTkinter

### 🚀 Installation Rapide

```bash
# Clonez le repo
git clone https://github.com/votreusername/FuturInteriorAI.git
cd FuturInteriorAI

# Installation automatique
python scripts/setup.py

# Ou manuellement
python -m venv venv
source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt
