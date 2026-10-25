# Farmers' Market — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.0.1** package linked in [this release](https://github.com/dafke1305/FS25_FarmersMarket/releases/tag/v1.0.0.1). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_FarmersMarket.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Sell goods

1. Open **ESC > Farmers' Market > New offer**.
2. Choose a supported source owned by your farm, the available product, quantity and offer duration. Supported stock can include bulk, pallets/bigbags and bales; the source must be recognized by the market.
3. Review the reference and price. The **server selects the best valid selling point and locks the goods price when you publish**; the price display is not an unrestricted custom-price field.
4. Publish once and wait for confirmation. Goods move out of usable stock into the protected virtual market depot. Detach pallets/bales from vehicles or implements before offering them.
5. Manage your listings under **My offers**. Withdrawing an unsold offer returns its unsold depot goods; do not sell or use those goods again through another route while they are reserved.

## Buy and arrange delivery

1. Under **Market**, select an offer, read its quantity/price and choose an eligible destination with enough capacity.
2. Choose the available delivery option: **Collect yourself**, **Arrange transport**, or **Express delivery**. Review the confirmation before committing money.
3. Self-pickup uses your own equipment and operating costs, without a carrier reward, contribution or subsidy.
4. Player transport appears in the normal **Contracts** screen. The carrier accepts the job and uses its pickup/loading instructions with suitable equipment. Keep the assigned carrier farm and selected destination consistent.
5. Express delivery transfers goods directly into the selected compatible storage and creates no haulage job. An eligible existing, unloaded purchase can also be converted to express: only the express fee is charged then, not the goods again. Loaded goods or a job claimed by another carrier can block conversion.

For physical delivery, follow the contract's loading instructions and bring the cargo into its selected destination area. This version checks delivery automatically; remain nearby as the carrier and wait for completion. Partial delivery does not settle the entire job until all required goods arrive.

## Administration and troubleshooting

- **Refresh inventory** updates source availability. An occupied original loading area, unsupported storage, insufficient capacity or a transfer still in progress can prevent the next operation.
- Listings belong to farms; another farm's source/stock is not your own inventory. Duration and delivery deadlines use game time.
- Depot, cargo and money must remain consistent in the savegame. Keep a complete save backup before administrative recovery.
- **Verify and resume**, **Restore goods** and **Recover depot** are specific recovery operations, not ordinary sale buttons. Check the exact confirmation and the original goods/payment state first.
- **Admin: force remove** stops processing and removes list/contract entries. It does **not** return/delete goods, pay anyone or refund reserved funds. Do not use it as a routine cancellation or a stock reset.
- If recovery cannot be proven safe, report the logs and offer ID instead of repeatedly recreating cargo or replaying payment.

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_FarmersMarket/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
