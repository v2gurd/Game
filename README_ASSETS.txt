NEON DRIVE ULTRA — Local 3D asset setup

Required repository layout:
/
  index.html
  assets/
    ferrari.glb
    ferrari_ao.png        (if referenced by the GLB)
    LittlestTokyo.glb

This index.html loads models from local repository paths:
  ./assets/ferrari.glb
  ./assets/LittlestTokyo.glb

Download the binary assets and save them with these exact filenames:

Ferrari GLB:
https://github.com/mrdoob/three.js/raw/refs/heads/dev/examples/models/gltf/ferrari.glb

City GLB:
https://github.com/mrdoob/three.js/raw/refs/heads/dev/examples/models/gltf/LittlestTokyo.glb

Ferrari AO texture, if required:
https://github.com/mrdoob/three.js/raw/refs/heads/dev/examples/models/gltf/ferrari_ao.png

Then upload all downloaded files into the assets/ folder in your GitHub repository.
GitHub Pages paths are case-sensitive.

IMPORTANT:
The ZIP contains the updated HTML and this guide, NOT the binary GLB files. This runtime could not retrieve the binary downloads, so the assets must be downloaded using the links above and added to assets/.
The LittlestTokyo model is a stylized sample environment, not a large photorealistic open-world city.
Three.js JavaScript modules still load from jsDelivr via the import map, but the 3D model files will be served by your own GitHub Pages repository.
Check the Three.js repository's asset attribution/license notices before public redistribution.
