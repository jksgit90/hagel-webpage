# SEO-plan — Hagel (indieband, Göteborg)

## Verklighetscheck
Det här är en enda statisk sida för ett lokalt band, inte ett företag som konkurrerar om sökvolym. Målet är inte att ranka för generiska termer ("indie band") utan att:
1. Vara #1-träffen när någon googlar **"Hagel band"** / **"Hagel Göteborg"** efter att ha sett bandet live eller på Instagram.
2. Ge Google tillräckligt med struktur för att visa rätt namn, bild och länkar (Spotify/Instagram/TikTok) direkt i sökresultatet.
3. Dela bra på sociala medier (OG-bild/titel korrekt).

Ingen blogg, inget content-kalender, ingen länkbygge-kampanj är motiverat i den här skalan — det hade varit resursslöseri för en enda landningssida.

## Fynd från research
- Bandet finns redan på Spotify med artist-ID `61nm4usiYZKQC0ZbLTBsvV` — sajten länkar just nu till `0cJkock96R16EJwqNdNcrC`. **Detta bör verifieras**, annars pekar musiklänken fel.
- Ingen direkt SEO-konkurrent finns; Göteborgs indiescen (Nektar, Westkust m.fl.) syns via playlists och pressartiklar, inte via egna optimerade sajter.
- Låg sökvolym på bandnamnet idag (~47 månatliga Spotify-lyssnare) — SEO-arbetet ska stödja upptäckt, inte driva den.

## Fas 1 — Teknisk grund (gör nu, ~1–2 timmar arbete)
- [ ] `<link rel="canonical" href="https://hagelgbg.se/">`
- [ ] Favicon (`<link rel="icon">`) baserad på loggan
- [ ] Open Graph + Twitter Card-taggar (titel, beskrivning, delningsbild, url)
- [ ] `robots.txt` (enkel, tillåt allt)
- [ ] JSON-LD strukturerad data, typ `MusicGroup`, med `sameAs`-länkar till Spotify/Instagram/TikTok
- [ ] Semantisk `<h1>` på bandnamnet i heron (visuellt oförändrad)
- [ ] Verifiera/rätta Spotify artist-ID i länken
- [ ] Registrera sajten i Google Search Console när `hagelgbg.se` är live (DNS + CNAME är redan på plats)

## Fas 2 — Synlighet utanför sajten (löpande, lågt underhåll)
- [ ] Lägg sajtens URL i bio på Spotify for Artists, Instagram, TikTok, YouTube — varje sådan länk är en gratis, relevant backlink
- [ ] Om spelningar bokas: lägg upp på Songkick/Bandsintown — dessa indexeras väl och länkar tillbaka
- [ ] Om bandet nämns i lokal press/blogg (Göteborgs Fria, lokala musikbloggar): be om länk till sajten, inte bara Spotify

## Fas 3 — Endast om bandet växer
- [ ] "Spelningar"-sida med kommande datum (färskt innehåll = anledning för Google att krypa om sidan igen)
- [ ] Pressbilder + pressmeddelande-sida om bokning/PR blir aktuellt

## KPI — realistiska mål
Ingen baseline finns ännu (sajten är inte live på custom domain). Första riktiga mätpunkten sätts när Search Console är kopplad, ca 2–4 veckor efter lansering.

| Mätpunkt | Mål |
|---|---|
| Rankar #1 på "Hagel Göteborg" / "Hagel band" | Inom 4–6 veckor efter indexering |
| Sidan indexerad i Google | Inom 1–2 veckor efter DNS/Search Console |
| OG-förhandsvisning korrekt på Instagram/iMessage | Direkt efter Fas 1 |

## Prioritering
Gör Fas 1 — det är den enda delen med tydlig, mätbar effekt för en sajt i den här storleken. Fas 2 är gratis och görs i samband med normal social media-hantering. Fas 3 är villkorad på om bandet börjar boka spelningar.
