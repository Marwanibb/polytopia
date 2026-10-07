# Battle of the Tiles

Een turn-based strategiegame in één HTML-bestand. Via GitHub Pages zet je hem online, en dankzij een player card speel je hem direct in een post op X.

## Online zetten (GitHub Pages)

1. Maak op GitHub een nieuwe openbare repository met de naam `battle-of-the-tiles`.
2. Upload `index.html`, `preview.png` en `.nojekyll` naar de hoofdmap van de repository.
3. Ga naar **Settings → Pages**, zet **Source** op *Deploy from a branch*, kies `main` en `/ (root)` en klik op Save.
4. Na ongeveer een minuut staat de game op `https://JOUW-GEBRUIKERSNAAM.github.io/battle-of-the-tiles/`.

## Je gegevens invullen

Open `index.html` en vervang in de `<head>`:

- `YOUR-USERNAME` door je GitHub-gebruikersnaam (staat er 6 keer in).
- `@YOUR-X-HANDLE` door je X-naam.

Heet je repository anders dan `battle-of-the-tiles`, pas dat deel van de links dan ook aan. Sla de wijziging op (Commit changes).

## Delen op X

Plaats de kale link `https://JOUW-GEBRUIKERSNAAM.github.io/battle-of-the-tiles/` in een post. X leest de `twitter:card="player"`-tags en toont de game in een venster in de post. Apps en clients die dat niet ondersteunen, tonen `preview.png` met de link.

## Goed om te weten

- Alle links in de card-tags moeten volledige `https://`-links zijn. GitHub Pages regelt dat voor je.
- X onthoudt kaarten een tijdje. Pas je de tags aan nadat je al gepost hebt, dan kan het even duren voordat een nieuwe post de wijziging laat zien.
- Solo, hotseat-multiplayer en de tutorial werken overal. Online kamers werken alleen in de claude.ai-versie; in het Multiplayer-menu staat dat erbij.
- Muziek en geluidseffecten worden in de browser gemaakt en starten na je eerste tik, omdat browsers geluid daarvoor blokkeren. Zet ze uit of zachter bij Settings.
- Opgeslagen games, instellingen en high scores staan in de opslag van je browser. In het venster op X kan de browser dat blokkeren. De game werkt dan nog steeds, maar onthoudt niets.
