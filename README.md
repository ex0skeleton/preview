# Preview Wiz 1.3

Extract the ZIP and copy its contents into your repository with index.html at the root. Commit and push. In GitHub Settings > Pages, deploy from your main branch and / (root). Test locally with VS Code Live Server.

Files are processed locally. PSD files require a saved composite. AI files require PDF compatibility; artwork outside artboards generally cannot be shown. HEIC/HEIF and the first page of TIFF files are decoded locally. CDR and EPS display a supported embedded preview only when available; previews may be outdated or low resolution. EPS without an embedded TIFF preview, or CDR without a supported embedded thumbnail, should be exported as PDF using the original software. Sound playback remains subject to browser audio policies. Fonts are loaded from Google Fonts if available.

Editable JavaScript and packages are in source/. The app is ready to use; rebuilding is optional. To rebuild, run npm install in source/, then npx esbuild app-source.js --bundle --format=esm --outfile=../app.js --minify.
