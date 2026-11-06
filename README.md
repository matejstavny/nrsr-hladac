# Hľadač prepisov NRSR

Záložka (bookmarklet) pre [tv.nrsr.sk](https://tv.nrsr.sk/archiv/schodza), ktorá:

- vyhľadá vetu v prepisoch schôdze Národnej rady SR,
- pustí video presne na jej začiatok (presný čas dopočíta Whisper v prehliadači),
- v režime **Strih** stiahne vybraný úsek ako MP4 bez prekódovania.

**Inštalácia:** otvor stránku tohto repozitára na GitHub Pages a pretiahni tlačidlo „Hľadať v NRSR“ na lištu záložiek.

## Súbory
- `index.html` – inštalačná stránka
- `hladac.js` – samotný hľadač; záložka si ho pri každom spustení načíta odtiaľto, takže nová verzia = nahradiť tento súbor

## Požiadavky
Aktuálny Chrome alebo Safari s WebGPU (Mac s čipom M). Pri prvom použití sa do prehliadača stiahne model Whisper (~1,6 GB) a nástroj na strih (~30 MB).
