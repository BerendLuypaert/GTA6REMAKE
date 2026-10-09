# Neon Valley — 3D Open World Browser Game

Een volledig speelbare low-poly Three.js open-world game, gemaakt met Vite en JavaScript.

## Lokaal starten

```bash
npm install
npm run dev
```

Besturing: ZQSD/pijltjes bewegen (Z vooruit, S achteruit, Q links, D rechts), muis slepen om rond te kijken, scrollen om te zoomen, Shift sprinten, Space springen, E interactie en Escape pauzeren.

## Build en GitHub Pages

```bash
npm run build
```

De workflow in `.github/workflows/pages.yml` bouwt automatisch `dist` en publiceert die naar GitHub Pages bij elke push naar `main`. Zet in GitHub bij **Settings → Pages** de source op **GitHub Actions**.

De Vite base path is ingesteld op `/GTA6REMAKE/`, passend bij de repository.

De bronbestanden staan in `src/`; de gegenereerde productieversie staat ook in de repository-root zodat de bestaande Pages-branch direct kan renderen.
