# public/models — Modèles 3D fournis (glTF)

Déposer ici les fichiers `.glb`, puis les déclarer dans `src/services/models.js` (MANIFEST).
Convention complète : `docs/context/08-assets-3d.md`.

L'essentiel :
- Nom : `<speciesId>.glb` (ex. `pommier.glb`), variantes `<speciesId>-2.glb`, `-3`…
- Format : **glTF binaire (.glb)**, textures embarquées.
- Axes/échelle : **Y vers le haut**, **mètres**, origine à la **base du tronc** (le service re-normalise, mais autant partir propre).
- Budget : **≤ 15 000 triangles** par arbre, 1–2 matériaux, textures ≤ 1024px.
- Licence : CC0 ou achetée avec droit d'usage app — consigner la source dans docs/context/08-assets-3d.md (tableau des assets).
