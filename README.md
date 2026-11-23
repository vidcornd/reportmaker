# Rapor AI — Surum Dagitimi

Bu repo yalnizca Rapor AI'nin guncelleme manifestini (`version.json`) ve
kurulum dosyalarini (Releases) barindirir. Kaynak kod burada degildir.

- Kurulu uygulama her acilista
  `https://raw.githubusercontent.com/vidcornd/reportmaker/main/version.json`
  dosyasini okur; `latest` kendi surumunden farkliysa kendi platformunun
  adresindeki paketi indirip kurar: Windows `url` (setup), Apple Silicon
  Mac `url_mac` (zip), Intel Mac `url_mac_intel` (zip). Platformun alani
  yoksa o platformda guncelleme yapilmaz.
- Yeni surum: once Releases'a `vX.Y.Z` etiketiyle `RaporAI_Setup.exe`,
  `RaporAI_mac_vX.Y.Z.zip/.pkg` (Apple Silicon) ve
  `RaporAI_mac_intel_vX.Y.Z.zip/.pkg` (Intel) yuklenir (Mac surum kaydinda
  `url_mac` ve `url_mac_intel`), SONRA `version.json`'a surum eklenip `latest` guncellenir.

> `latest` degistigi anda tum kurulumlar guncellenir. Setup yuklenmeden
> `version.json` degistirilmemelidir.
