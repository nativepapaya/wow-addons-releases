# WoW addon releases

Public release downloads for WoW addons and their companion tools. Development is maintained separately; this repository contains release documentation and downloadable release assets, not user data or development history.

## QuietPrices

QuietPrices displays TSM public auction snapshots in WoW Forever item tooltips. Its Windows desktop updater maintains the price data separately from the addon and offers explicit software-update controls.

Download packages from [Releases](https://github.com/nativepapaya/wow-addons-releases/releases). QuietPrices releases use tags of the form `quietprices-vX.Y.Z`. Read the instructions and licences included with each package. Current market support is limited to the verified US Normal mapping.

The Windows executable is unsigned. SHA-256 hashes and archive validation check integrity; they are not an independent publisher signature. Update clients trust this fixed GitHub repository over HTTPS. Do not disable Windows security protections to run an unexpected or blocked download.

Addon Lua source is included in the addon package. Bundled Python executable code should not be treated as secret. Original QuietPrices code is MIT licensed; bundled runtimes retain their own licences. Auction data belongs to its providers and is not covered by the code licence.

Pricing source: [TradeSkillMaster public data](https://tradeskillmaster.com/public-data). Prices are delayed snapshots, not live offers or sale guarantees. This project is not endorsed by Blizzard Entertainment or TradeSkillMaster.

No game files, account settings, credentials, downloaded price snapshots, or local deployment records are published here.
