# Rapor AI — Surum Dagitimi

Bu repo yalnizca Rapor AI'nin guncelleme manifestini (`version.json`) ve
kurulum dosyalarini (Releases) barindirir. Kaynak kod burada degildir.

- Kurulu uygulama her acilista
  `https://raw.githubusercontent.com/vidcornd/reportmaker/main/version.json`
  dosyasini okur; `latest` kendi surumunden farkliysa ilgili `url`'deki
  setup'i indirip sessizce kurar.
- Yeni surum: once Releases'a `vX.Y.Z` etiketiyle `RaporAI_Setup.exe`
  yuklenir, SONRA `version.json`'a surum eklenip `latest` guncellenir.

> `latest` degistigi anda tum kurulumlar guncellenir. Setup yuklenmeden
> `version.json` degistirilmemelidir.
