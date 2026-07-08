---
title: Sell Prices
description: Full /sell price list for every sellable item on HavenCraft — sortable, searchable, with item icons.
published: true
date: 2026-07-08T12:00:00.000Z
tags: items, economy, sell
editor: markdown
dateCreated: 2026-07-08T12:00:00.000Z
---

# Sell Prices

Every price the server's `/sell` command will pay for an item, straight from `worth.yml`. Sell a single item in hand with `/sell hand`, your whole inventory with `/sell all`, or a specific item and amount with `/sell <item> <amount>`.

Prices get tuned as the server economy evolves — this page reflects the current values, but always trust the in-game price over a stale memory of this list.

1422 items are covered here (1378 with icons; a handful of newer or purely decorative items don't have a standalone sprite and show a blank swatch).

<div id="sell-prices-app">
<input id="sp-filter" type="text" placeholder="Filter by item or category…" autocomplete="off">
<div id="sp-count"></div>
<div class="sp-table-wrap">
<table id="sp-table">
<thead>
<tr>
<th class="sp-sort" data-sort="icon">Icon</th>
<th class="sp-sort" data-sort="name">Item</th>
<th class="sp-sort" data-sort="category">Category</th>
<th class="sp-sort" data-sort="price">Sell Price</th>
</tr>
</thead>
<tbody>
<tr data-name="charcoal" data-category="fuel &amp; the primary grind" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/charcoal.png" alt="" loading="lazy"></span></td>
<td>Charcoal</td>
<td>Fuel &amp; the Primary Grind</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="coal" data-category="fuel &amp; the primary grind" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/coal.png" alt="" loading="lazy"></span></td>
<td>Coal</td>
<td>Fuel &amp; the Primary Grind</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="coal block" data-category="fuel &amp; the primary grind" data-price="90">
<td><span class="sp-icon"><img src="/assets/items/sell/coalblock.png" alt="" loading="lazy"></span></td>
<td>Coal Block</td>
<td>Fuel &amp; the Primary Grind</td>
<td class="sp-price">$90.00</td>
</tr>
<tr data-name="iron ingot" data-category="iron" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/ironingot.png" alt="" loading="lazy"></span></td>
<td>Iron Ingot</td>
<td>Iron</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="iron block" data-category="iron" data-price="54">
<td><span class="sp-icon"><img src="/assets/items/sell/ironblock.png" alt="" loading="lazy"></span></td>
<td>Iron Block</td>
<td>Iron</td>
<td class="sp-price">$54.00</td>
</tr>
<tr data-name="iron nugget" data-category="iron" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/ironnugget.png" alt="" loading="lazy"></span></td>
<td>Iron Nugget</td>
<td>Iron</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="raw iron" data-category="iron" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/rawiron.png" alt="" loading="lazy"></span></td>
<td>Raw Iron</td>
<td>Iron</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="raw iron block" data-category="iron" data-price="45">
<td><span class="sp-icon"><img src="/assets/items/sell/rawironblock.png" alt="" loading="lazy"></span></td>
<td>Raw Iron Block</td>
<td>Iron</td>
<td class="sp-price">$45.00</td>
</tr>
<tr data-name="iron ore" data-category="iron" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/ironore.png" alt="" loading="lazy"></span></td>
<td>Iron Ore</td>
<td>Iron</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="deepslate iron ore" data-category="iron" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslateironore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Iron Ore</td>
<td>Iron</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="gold ingot" data-category="gold" data-price="9">
<td><span class="sp-icon"><img src="/assets/items/sell/goldingot.png" alt="" loading="lazy"></span></td>
<td>Gold Ingot</td>
<td>Gold</td>
<td class="sp-price">$9.00</td>
</tr>
<tr data-name="gold block" data-category="gold" data-price="81">
<td><span class="sp-icon"><img src="/assets/items/sell/goldblock.png" alt="" loading="lazy"></span></td>
<td>Gold Block</td>
<td>Gold</td>
<td class="sp-price">$81.00</td>
</tr>
<tr data-name="gold nugget" data-category="gold" data-price="0.85">
<td><span class="sp-icon"><img src="/assets/items/sell/goldnugget.png" alt="" loading="lazy"></span></td>
<td>Gold Nugget</td>
<td>Gold</td>
<td class="sp-price">$0.85</td>
</tr>
<tr data-name="raw gold" data-category="gold" data-price="8">
<td><span class="sp-icon"><img src="/assets/items/sell/rawgold.png" alt="" loading="lazy"></span></td>
<td>Raw Gold</td>
<td>Gold</td>
<td class="sp-price">$8.00</td>
</tr>
<tr data-name="raw gold block" data-category="gold" data-price="72">
<td><span class="sp-icon"><img src="/assets/items/sell/rawgoldblock.png" alt="" loading="lazy"></span></td>
<td>Raw Gold Block</td>
<td>Gold</td>
<td class="sp-price">$72.00</td>
</tr>
<tr data-name="gold ore" data-category="gold" data-price="8">
<td><span class="sp-icon"><img src="/assets/items/sell/goldore.png" alt="" loading="lazy"></span></td>
<td>Gold Ore</td>
<td>Gold</td>
<td class="sp-price">$8.00</td>
</tr>
<tr data-name="deepslate gold ore" data-category="gold" data-price="8">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslategoldore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Gold Ore</td>
<td>Gold</td>
<td class="sp-price">$8.00</td>
</tr>
<tr data-name="nether gold ore" data-category="gold" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/nethergoldore.png" alt="" loading="lazy"></span></td>
<td>Nether Gold Ore</td>
<td>Gold</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="copper ingot" data-category="copper" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/copperingot.png" alt="" loading="lazy"></span></td>
<td>Copper Ingot</td>
<td>Copper</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="copper block" data-category="copper" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/copperblock.png" alt="" loading="lazy"></span></td>
<td>Copper Block</td>
<td>Copper</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="raw copper" data-category="copper" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/rawcopper.png" alt="" loading="lazy"></span></td>
<td>Raw Copper</td>
<td>Copper</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="raw copper block" data-category="copper" data-price="10.8">
<td><span class="sp-icon"><img src="/assets/items/sell/rawcopperblock.png" alt="" loading="lazy"></span></td>
<td>Raw Copper Block</td>
<td>Copper</td>
<td class="sp-price">$10.80</td>
</tr>
<tr data-name="copper ore" data-category="copper" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/copperore.png" alt="" loading="lazy"></span></td>
<td>Copper Ore</td>
<td>Copper</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="deepslate copper ore" data-category="copper" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatecopperore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Copper Ore</td>
<td>Copper</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="diamond" data-category="diamond" data-price="200">
<td><span class="sp-icon"><img src="/assets/items/sell/diamond.png" alt="" loading="lazy"></span></td>
<td>Diamond</td>
<td>Diamond</td>
<td class="sp-price">$200.00</td>
</tr>
<tr data-name="diamond block" data-category="diamond" data-price="1800">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondblock.png" alt="" loading="lazy"></span></td>
<td>Diamond Block</td>
<td>Diamond</td>
<td class="sp-price">$1800.00</td>
</tr>
<tr data-name="diamond ore" data-category="diamond" data-price="200">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondore.png" alt="" loading="lazy"></span></td>
<td>Diamond Ore</td>
<td>Diamond</td>
<td class="sp-price">$200.00</td>
</tr>
<tr data-name="deepslate diamond ore" data-category="diamond" data-price="200">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatediamondore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Diamond Ore</td>
<td>Diamond</td>
<td class="sp-price">$200.00</td>
</tr>
<tr data-name="emerald" data-category="emerald" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/emerald.png" alt="" loading="lazy"></span></td>
<td>Emerald</td>
<td>Emerald</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="emerald block" data-category="emerald" data-price="45">
<td><span class="sp-icon"><img src="/assets/items/sell/emeraldblock.png" alt="" loading="lazy"></span></td>
<td>Emerald Block</td>
<td>Emerald</td>
<td class="sp-price">$45.00</td>
</tr>
<tr data-name="emerald ore" data-category="emerald" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/emeraldore.png" alt="" loading="lazy"></span></td>
<td>Emerald Ore</td>
<td>Emerald</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="deepslate emerald ore" data-category="emerald" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslateemeraldore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Emerald Ore</td>
<td>Emerald</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="lapis lazuli" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lapislazuli.png" alt="" loading="lazy"></span></td>
<td>Lapis Lazuli</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="lapis block" data-category="lapis / redstone" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lapisblock.png" alt="" loading="lazy"></span></td>
<td>Lapis Block</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="lapis ore" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lapisore.png" alt="" loading="lazy"></span></td>
<td>Lapis Ore</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="deepslate lapis ore" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatelapisore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Lapis Ore</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="redstone" data-category="lapis / redstone" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/redstone.png" alt="" loading="lazy"></span></td>
<td>Redstone</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="redstone block" data-category="lapis / redstone" data-price="9">
<td><span class="sp-icon"><img src="/assets/items/sell/redstoneblock.png" alt="" loading="lazy"></span></td>
<td>Redstone Block</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$9.00</td>
</tr>
<tr data-name="redstone ore" data-category="lapis / redstone" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/redstoneore.png" alt="" loading="lazy"></span></td>
<td>Redstone Ore</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="deepslate redstone ore" data-category="lapis / redstone" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslateredstoneore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Redstone Ore</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="quartz" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/quartz.png" alt="" loading="lazy"></span></td>
<td>Quartz</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="quartz block" data-category="lapis / redstone" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/quartzblock.png" alt="" loading="lazy"></span></td>
<td>Quartz Block</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="nether quartz ore" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/netherquartzore.png" alt="" loading="lazy"></span></td>
<td>Nether Quartz Ore</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="amethyst shard" data-category="lapis / redstone" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/amethystshard.png" alt="" loading="lazy"></span></td>
<td>Amethyst Shard</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="amethyst block" data-category="lapis / redstone" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/amethystblock.png" alt="" loading="lazy"></span></td>
<td>Amethyst Block</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="netherite ingot" data-category="lapis / redstone" data-price="1280">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteingot.png" alt="" loading="lazy"></span></td>
<td>Netherite Ingot</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$1280.00</td>
</tr>
<tr data-name="netherite block" data-category="lapis / redstone" data-price="11520">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteblock.png" alt="" loading="lazy"></span></td>
<td>Netherite Block</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$11520.00</td>
</tr>
<tr data-name="netherite scrap" data-category="lapis / redstone" data-price="272">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritescrap.png" alt="" loading="lazy"></span></td>
<td>Netherite Scrap</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$272.00</td>
</tr>
<tr data-name="ancient debris" data-category="lapis / redstone" data-price="272">
<td><span class="sp-icon"><img src="/assets/items/sell/ancientdebris.png" alt="" loading="lazy"></span></td>
<td>Ancient Debris</td>
<td>Lapis / Redstone</td>
<td class="sp-price">$272.00</td>
</tr>
<tr data-name="rotten flesh" data-category="mob drops" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/rottenflesh.png" alt="" loading="lazy"></span></td>
<td>Rotten Flesh</td>
<td>Mob Drops</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="bone" data-category="mob drops" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/bone.png" alt="" loading="lazy"></span></td>
<td>Bone</td>
<td>Mob Drops</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="bone meal" data-category="mob drops" data-price="0.13">
<td><span class="sp-icon"><img src="/assets/items/sell/bonemeal.png" alt="" loading="lazy"></span></td>
<td>Bone Meal</td>
<td>Mob Drops</td>
<td class="sp-price">$0.13</td>
</tr>
<tr data-name="bone block" data-category="mob drops" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/boneblock.png" alt="" loading="lazy"></span></td>
<td>Bone Block</td>
<td>Mob Drops</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="string" data-category="mob drops" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/string.png" alt="" loading="lazy"></span></td>
<td>String</td>
<td>Mob Drops</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="spider eye" data-category="mob drops" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/spidereye.png" alt="" loading="lazy"></span></td>
<td>Spider Eye</td>
<td>Mob Drops</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="gunpowder" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/gunpowder.png" alt="" loading="lazy"></span></td>
<td>Gunpowder</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="ender pearl" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/enderpearl.png" alt="" loading="lazy"></span></td>
<td>Ender Pearl</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="ender eye" data-category="mob drops" data-price="3.5">
<td><span class="sp-icon"><img src="/assets/items/sell/endereye.png" alt="" loading="lazy"></span></td>
<td>Ender Eye</td>
<td>Mob Drops</td>
<td class="sp-price">$3.50</td>
</tr>
<tr data-name="blaze rod" data-category="mob drops" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/blazerod.png" alt="" loading="lazy"></span></td>
<td>Blaze Rod</td>
<td>Mob Drops</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="blaze powder" data-category="mob drops" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blazepowder.png" alt="" loading="lazy"></span></td>
<td>Blaze Powder</td>
<td>Mob Drops</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="ghast tear" data-category="mob drops" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/ghasttear.png" alt="" loading="lazy"></span></td>
<td>Ghast Tear</td>
<td>Mob Drops</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="slime ball" data-category="mob drops" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/slimeball.png" alt="" loading="lazy"></span></td>
<td>Slime Ball</td>
<td>Mob Drops</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="slime block" data-category="mob drops" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/slimeblock.png" alt="" loading="lazy"></span></td>
<td>Slime Block</td>
<td>Mob Drops</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="magma cream" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/magmacream.png" alt="" loading="lazy"></span></td>
<td>Magma Cream</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="magma block" data-category="mob drops" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/magmablock.png" alt="" loading="lazy"></span></td>
<td>Magma Block</td>
<td>Mob Drops</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="phantom membrane" data-category="mob drops" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/phantommembrane.png" alt="" loading="lazy"></span></td>
<td>Phantom Membrane</td>
<td>Mob Drops</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="prismarine shard" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarineshard.png" alt="" loading="lazy"></span></td>
<td>Prismarine Shard</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="prismarine crystals" data-category="mob drops" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinecrystals.png" alt="" loading="lazy"></span></td>
<td>Prismarine Crystals</td>
<td>Mob Drops</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="ink sac" data-category="mob drops" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/inksac.png" alt="" loading="lazy"></span></td>
<td>Ink Sac</td>
<td>Mob Drops</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="glow ink sac" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/glowinksac.png" alt="" loading="lazy"></span></td>
<td>Glow Ink Sac</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="leather" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/leather.png" alt="" loading="lazy"></span></td>
<td>Leather</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="rabbit hide" data-category="mob drops" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/rabbithide.png" alt="" loading="lazy"></span></td>
<td>Rabbit Hide</td>
<td>Mob Drops</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="rabbit foot" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/rabbitfoot.png" alt="" loading="lazy"></span></td>
<td>Rabbit Foot</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="feather" data-category="mob drops" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/feather.png" alt="" loading="lazy"></span></td>
<td>Feather</td>
<td>Mob Drops</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="egg" data-category="mob drops" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/egg.png" alt="" loading="lazy"></span></td>
<td>Egg</td>
<td>Mob Drops</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="turtle scute" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/turtlescute.png" alt="" loading="lazy"></span></td>
<td>Turtle Scute</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="honeycomb" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/honeycomb.png" alt="" loading="lazy"></span></td>
<td>Honeycomb</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="honeycomb block" data-category="mob drops" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/honeycombblock.png" alt="" loading="lazy"></span></td>
<td>Honeycomb Block</td>
<td>Mob Drops</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="honey bottle" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/honeybottle.png" alt="" loading="lazy"></span></td>
<td>Honey Bottle</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="honey block" data-category="mob drops" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/honeyblock.png" alt="" loading="lazy"></span></td>
<td>Honey Block</td>
<td>Mob Drops</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="shulker shell" data-category="mob drops" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/shulkershell.png" alt="" loading="lazy"></span></td>
<td>Shulker Shell</td>
<td>Mob Drops</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="wither skeleton skull" data-category="mob drops" data-price="25">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Wither Skeleton Skull</td>
<td>Mob Drops</td>
<td class="sp-price">$25.00</td>
</tr>
<tr data-name="nether star" data-category="mob drops" data-price="50">
<td><span class="sp-icon"><img src="/assets/items/sell/netherstar.png" alt="" loading="lazy"></span></td>
<td>Nether Star</td>
<td>Mob Drops</td>
<td class="sp-price">$50.00</td>
</tr>
<tr data-name="dragon breath" data-category="mob drops" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/dragonbreath.png" alt="" loading="lazy"></span></td>
<td>Dragon Breath</td>
<td>Mob Drops</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="totem of undying" data-category="mob drops" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/totemofundying.png" alt="" loading="lazy"></span></td>
<td>Totem of Undying</td>
<td>Mob Drops</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="wheat" data-category="crops &amp; farm produce" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/wheat.png" alt="" loading="lazy"></span></td>
<td>Wheat</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="hay block" data-category="crops &amp; farm produce" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/hayblock.png" alt="" loading="lazy"></span></td>
<td>Hay Block</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="wheat seeds" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/wheatseeds.png" alt="" loading="lazy"></span></td>
<td>Wheat Seeds</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="carrot" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/carrot.png" alt="" loading="lazy"></span></td>
<td>Carrot</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="golden carrot" data-category="crops &amp; farm produce" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/goldencarrot.png" alt="" loading="lazy"></span></td>
<td>Golden Carrot</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="potato" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/potato.png" alt="" loading="lazy"></span></td>
<td>Potato</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="baked potato" data-category="crops &amp; farm produce" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/bakedpotato.png" alt="" loading="lazy"></span></td>
<td>Baked Potato</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="poisonous potato" data-category="crops &amp; farm produce" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/poisonouspotato.png" alt="" loading="lazy"></span></td>
<td>Poisonous Potato</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="beetroot" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/beetroot.png" alt="" loading="lazy"></span></td>
<td>Beetroot</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="beetroot seeds" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/beetrootseeds.png" alt="" loading="lazy"></span></td>
<td>Beetroot Seeds</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="melon" data-category="crops &amp; farm produce" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/melon.png" alt="" loading="lazy"></span></td>
<td>Melon</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="melon slice" data-category="crops &amp; farm produce" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/melonslice.png" alt="" loading="lazy"></span></td>
<td>Melon Slice</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="glistering melon slice" data-category="crops &amp; farm produce" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/glisteringmelonslice.png" alt="" loading="lazy"></span></td>
<td>Glistering Melon Slice</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="pumpkin" data-category="crops &amp; farm produce" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/pumpkin.png" alt="" loading="lazy"></span></td>
<td>Pumpkin</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="carved pumpkin" data-category="crops &amp; farm produce" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/carvedpumpkin.png" alt="" loading="lazy"></span></td>
<td>Carved Pumpkin</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pumpkin seeds" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/pumpkinseeds.png" alt="" loading="lazy"></span></td>
<td>Pumpkin Seeds</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="sugar cane" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/sugarcane.png" alt="" loading="lazy"></span></td>
<td>Sugar Cane</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="sugar" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/sugar.png" alt="" loading="lazy"></span></td>
<td>Sugar</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="paper" data-category="crops &amp; farm produce" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/paper.png" alt="" loading="lazy"></span></td>
<td>Paper</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="bamboo" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboo.png" alt="" loading="lazy"></span></td>
<td>Bamboo</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="bamboo block" data-category="crops &amp; farm produce" data-price="0.9">
<td><span class="sp-icon"><img src="/assets/items/sell/bambooblock.png" alt="" loading="lazy"></span></td>
<td>Bamboo Block</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.90</td>
</tr>
<tr data-name="cactus" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cactus.png" alt="" loading="lazy"></span></td>
<td>Cactus</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cocoa beans" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cocoabeans.png" alt="" loading="lazy"></span></td>
<td>Cocoa Beans</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="nether wart" data-category="crops &amp; farm produce" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/netherwart.png" alt="" loading="lazy"></span></td>
<td>Nether Wart</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="nether wart block" data-category="crops &amp; farm produce" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/netherwartblock.png" alt="" loading="lazy"></span></td>
<td>Nether Wart Block</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="sweet berries" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/sweetberries.png" alt="" loading="lazy"></span></td>
<td>Sweet Berries</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="glow berries" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/glowberries.png" alt="" loading="lazy"></span></td>
<td>Glow Berries</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="red mushroom" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/redmushroom.png" alt="" loading="lazy"></span></td>
<td>Red Mushroom</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="brown mushroom" data-category="crops &amp; farm produce" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/brownmushroom.png" alt="" loading="lazy"></span></td>
<td>Brown Mushroom</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="apple" data-category="crops &amp; farm produce" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/apple.png" alt="" loading="lazy"></span></td>
<td>Apple</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="golden apple" data-category="crops &amp; farm produce" data-price="72">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenapple.png" alt="" loading="lazy"></span></td>
<td>Golden Apple</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$72.00</td>
</tr>
<tr data-name="chorus fruit" data-category="crops &amp; farm produce" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chorusfruit.png" alt="" loading="lazy"></span></td>
<td>Chorus Fruit</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="popped chorus fruit" data-category="crops &amp; farm produce" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/poppedchorusfruit.png" alt="" loading="lazy"></span></td>
<td>Popped Chorus Fruit</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="kelp" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/kelp.png" alt="" loading="lazy"></span></td>
<td>Kelp</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="dried kelp" data-category="crops &amp; farm produce" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/driedkelp.png" alt="" loading="lazy"></span></td>
<td>Dried Kelp</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dried kelp block" data-category="crops &amp; farm produce" data-price="1.8">
<td><span class="sp-icon"><img src="/assets/items/sell/driedkelpblock.png" alt="" loading="lazy"></span></td>
<td>Dried Kelp Block</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$1.80</td>
</tr>
<tr data-name="bread" data-category="prepared foods" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/bread.png" alt="" loading="lazy"></span></td>
<td>Bread</td>
<td>Prepared Foods</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="cookie" data-category="prepared foods" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cookie.png" alt="" loading="lazy"></span></td>
<td>Cookie</td>
<td>Prepared Foods</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cake" data-category="prepared foods" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/cake.png" alt="" loading="lazy"></span></td>
<td>Cake</td>
<td>Prepared Foods</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="pumpkin pie" data-category="prepared foods" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/pumpkinpie.png" alt="" loading="lazy"></span></td>
<td>Pumpkin Pie</td>
<td>Prepared Foods</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="mushroom stew" data-category="prepared foods" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/mushroomstew.png" alt="" loading="lazy"></span></td>
<td>Mushroom Stew</td>
<td>Prepared Foods</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="rabbit stew" data-category="prepared foods" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/rabbitstew.png" alt="" loading="lazy"></span></td>
<td>Rabbit Stew</td>
<td>Prepared Foods</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="beetroot soup" data-category="prepared foods" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/beetrootsoup.png" alt="" loading="lazy"></span></td>
<td>Beetroot Soup</td>
<td>Prepared Foods</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="suspicious stew" data-category="prepared foods" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/suspiciousstew.png" alt="" loading="lazy"></span></td>
<td>Suspicious Stew</td>
<td>Prepared Foods</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="beef" data-category="meats" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/beef.png" alt="" loading="lazy"></span></td>
<td>Beef</td>
<td>Meats</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cooked beef" data-category="meats" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedbeef.png" alt="" loading="lazy"></span></td>
<td>Cooked Beef</td>
<td>Meats</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="porkchop" data-category="meats" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/porkchop.png" alt="" loading="lazy"></span></td>
<td>Porkchop</td>
<td>Meats</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cooked porkchop" data-category="meats" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedporkchop.png" alt="" loading="lazy"></span></td>
<td>Cooked Porkchop</td>
<td>Meats</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="chicken" data-category="meats" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/chicken.png" alt="" loading="lazy"></span></td>
<td>Chicken</td>
<td>Meats</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cooked chicken" data-category="meats" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedchicken.png" alt="" loading="lazy"></span></td>
<td>Cooked Chicken</td>
<td>Meats</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="mutton" data-category="meats" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/mutton.png" alt="" loading="lazy"></span></td>
<td>Mutton</td>
<td>Meats</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cooked mutton" data-category="meats" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedmutton.png" alt="" loading="lazy"></span></td>
<td>Cooked Mutton</td>
<td>Meats</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="rabbit" data-category="meats" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/rabbit.png" alt="" loading="lazy"></span></td>
<td>Rabbit</td>
<td>Meats</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cooked rabbit" data-category="meats" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedrabbit.png" alt="" loading="lazy"></span></td>
<td>Cooked Rabbit</td>
<td>Meats</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cod" data-category="fishing" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/cod.png" alt="" loading="lazy"></span></td>
<td>Cod</td>
<td>Fishing</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="cooked cod" data-category="fishing" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedcod.png" alt="" loading="lazy"></span></td>
<td>Cooked Cod</td>
<td>Fishing</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="salmon" data-category="fishing" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/salmon.png" alt="" loading="lazy"></span></td>
<td>Salmon</td>
<td>Fishing</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cooked salmon" data-category="fishing" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cookedsalmon.png" alt="" loading="lazy"></span></td>
<td>Cooked Salmon</td>
<td>Fishing</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="tropical fish" data-category="fishing" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/tropicalfish.png" alt="" loading="lazy"></span></td>
<td>Tropical Fish</td>
<td>Fishing</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="pufferfish" data-category="fishing" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/pufferfish.png" alt="" loading="lazy"></span></td>
<td>Pufferfish</td>
<td>Fishing</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="oak log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/oaklog.png" alt="" loading="lazy"></span></td>
<td>Oak Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="spruce log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucelog.png" alt="" loading="lazy"></span></td>
<td>Spruce Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="birch log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/birchlog.png" alt="" loading="lazy"></span></td>
<td>Birch Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="jungle log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/junglelog.png" alt="" loading="lazy"></span></td>
<td>Jungle Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="acacia log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/acacialog.png" alt="" loading="lazy"></span></td>
<td>Acacia Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dark oak log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoaklog.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="mangrove log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovelog.png" alt="" loading="lazy"></span></td>
<td>Mangrove Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cherry log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrylog.png" alt="" loading="lazy"></span></td>
<td>Cherry Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pale oak log" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoaklog.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Log</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="crimson stem" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonstem.png" alt="" loading="lazy"></span></td>
<td>Crimson Stem</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="warped stem" data-category="wood" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedstem.png" alt="" loading="lazy"></span></td>
<td>Warped Stem</td>
<td>Wood</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="oak planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/oakplanks.png" alt="" loading="lazy"></span></td>
<td>Oak Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="spruce planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/spruceplanks.png" alt="" loading="lazy"></span></td>
<td>Spruce Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="birch planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/birchplanks.png" alt="" loading="lazy"></span></td>
<td>Birch Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="jungle planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/jungleplanks.png" alt="" loading="lazy"></span></td>
<td>Jungle Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="acacia planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciaplanks.png" alt="" loading="lazy"></span></td>
<td>Acacia Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dark oak planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakplanks.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mangrove planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveplanks.png" alt="" loading="lazy"></span></td>
<td>Mangrove Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="cherry planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryplanks.png" alt="" loading="lazy"></span></td>
<td>Cherry Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pale oak planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakplanks.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="crimson planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonplanks.png" alt="" loading="lazy"></span></td>
<td>Crimson Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedplanks.png" alt="" loading="lazy"></span></td>
<td>Warped Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="bamboo planks" data-category="wood" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bambooplanks.png" alt="" loading="lazy"></span></td>
<td>Bamboo Planks</td>
<td>Wood</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="stick" data-category="wood" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/stick.png" alt="" loading="lazy"></span></td>
<td>Stick</td>
<td>Wood</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cobblestone" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cobblestone.png" alt="" loading="lazy"></span></td>
<td>Cobblestone</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cobbled deepslate" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cobbleddeepslate.png" alt="" loading="lazy"></span></td>
<td>Cobbled Deepslate</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="stone" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stone.png" alt="" loading="lazy"></span></td>
<td>Stone</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslate.png" alt="" loading="lazy"></span></td>
<td>Deepslate</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="granite" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/granite.png" alt="" loading="lazy"></span></td>
<td>Granite</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="diorite" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diorite.png" alt="" loading="lazy"></span></td>
<td>Diorite</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="andesite" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/andesite.png" alt="" loading="lazy"></span></td>
<td>Andesite</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="tuff" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/tuff.png" alt="" loading="lazy"></span></td>
<td>Tuff</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="calcite" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/calcite.png" alt="" loading="lazy"></span></td>
<td>Calcite</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="dripstone block" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/dripstoneblock.png" alt="" loading="lazy"></span></td>
<td>Dripstone Block</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pointed dripstone" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/pointeddripstone.png" alt="" loading="lazy"></span></td>
<td>Pointed Dripstone</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dirt" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/dirt.png" alt="" loading="lazy"></span></td>
<td>Dirt</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="coarse dirt" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/coarsedirt.png" alt="" loading="lazy"></span></td>
<td>Coarse Dirt</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="rooted dirt" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/rooteddirt.png" alt="" loading="lazy"></span></td>
<td>Rooted Dirt</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="grass block" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/grassblock.png" alt="" loading="lazy"></span></td>
<td>Grass Block</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="podzol" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/podzol.png" alt="" loading="lazy"></span></td>
<td>Podzol</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mycelium" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mycelium.png" alt="" loading="lazy"></span></td>
<td>Mycelium</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mud" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/mud.png" alt="" loading="lazy"></span></td>
<td>Mud</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="sand" data-category="stone, dirt &amp; common building blocks" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/sand.png" alt="" loading="lazy"></span></td>
<td>Sand</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="red sand" data-category="stone, dirt &amp; common building blocks" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/redsand.png" alt="" loading="lazy"></span></td>
<td>Red Sand</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="gravel" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/gravel.png" alt="" loading="lazy"></span></td>
<td>Gravel</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="flint" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/flint.png" alt="" loading="lazy"></span></td>
<td>Flint</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="clay" data-category="stone, dirt &amp; common building blocks" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/clay.png" alt="" loading="lazy"></span></td>
<td>Clay</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="clay ball" data-category="stone, dirt &amp; common building blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/clayball.png" alt="" loading="lazy"></span></td>
<td>Clay Ball</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="sandstone" data-category="stone, dirt &amp; common building blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sandstone.png" alt="" loading="lazy"></span></td>
<td>Sandstone</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="red sandstone" data-category="stone, dirt &amp; common building blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redsandstone.png" alt="" loading="lazy"></span></td>
<td>Red Sandstone</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="glass" data-category="stone, dirt &amp; common building blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/glass.png" alt="" loading="lazy"></span></td>
<td>Glass</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="glass pane" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/glasspane.png" alt="" loading="lazy"></span></td>
<td>Glass Pane</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="brick" data-category="stone, dirt &amp; common building blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/brick.png" alt="" loading="lazy"></span></td>
<td>Brick</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="bricks" data-category="stone, dirt &amp; common building blocks" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bricks.png" alt="" loading="lazy"></span></td>
<td>Bricks</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="obsidian" data-category="stone, dirt &amp; common building blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/obsidian.png" alt="" loading="lazy"></span></td>
<td>Obsidian</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="crying obsidian" data-category="stone, dirt &amp; common building blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/cryingobsidian.png" alt="" loading="lazy"></span></td>
<td>Crying Obsidian</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="snowball" data-category="stone, dirt &amp; common building blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/snowball.png" alt="" loading="lazy"></span></td>
<td>Snowball</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="snow block" data-category="stone, dirt &amp; common building blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/snowblock.png" alt="" loading="lazy"></span></td>
<td>Snow Block</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="ice" data-category="stone, dirt &amp; common building blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ice.png" alt="" loading="lazy"></span></td>
<td>Ice</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="packed ice" data-category="stone, dirt &amp; common building blocks" data-price="0.9">
<td><span class="sp-icon"><img src="/assets/items/sell/packedice.png" alt="" loading="lazy"></span></td>
<td>Packed Ice</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.90</td>
</tr>
<tr data-name="blue ice" data-category="stone, dirt &amp; common building blocks" data-price="8.1">
<td><span class="sp-icon"><img src="/assets/items/sell/blueice.png" alt="" loading="lazy"></span></td>
<td>Blue Ice</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$8.10</td>
</tr>
<tr data-name="sponge" data-category="stone, dirt &amp; common building blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/sponge.png" alt="" loading="lazy"></span></td>
<td>Sponge</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="wet sponge" data-category="stone, dirt &amp; common building blocks" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/wetsponge.png" alt="" loading="lazy"></span></td>
<td>Wet Sponge</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="sea pickle" data-category="stone, dirt &amp; common building blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/seapickle.png" alt="" loading="lazy"></span></td>
<td>Sea Pickle</td>
<td>Stone, Dirt &amp; Common Building Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="netherrack" data-category="nether &amp; end blocks" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/netherrack.png" alt="" loading="lazy"></span></td>
<td>Netherrack</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="soul sand" data-category="nether &amp; end blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/soulsand.png" alt="" loading="lazy"></span></td>
<td>Soul Sand</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="soul soil" data-category="nether &amp; end blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/soulsoil.png" alt="" loading="lazy"></span></td>
<td>Soul Soil</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="basalt" data-category="nether &amp; end blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/basalt.png" alt="" loading="lazy"></span></td>
<td>Basalt</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="blackstone" data-category="nether &amp; end blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstone.png" alt="" loading="lazy"></span></td>
<td>Blackstone</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="gilded blackstone" data-category="nether &amp; end blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/gildedblackstone.png" alt="" loading="lazy"></span></td>
<td>Gilded Blackstone</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="glowstone dust" data-category="nether &amp; end blocks" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/glowstonedust.png" alt="" loading="lazy"></span></td>
<td>Glowstone Dust</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="glowstone" data-category="nether &amp; end blocks" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/glowstone.png" alt="" loading="lazy"></span></td>
<td>Glowstone</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="shroomlight" data-category="nether &amp; end blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/shroomlight.png" alt="" loading="lazy"></span></td>
<td>Shroomlight</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="nether brick" data-category="nether &amp; end blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbrick.png" alt="" loading="lazy"></span></td>
<td>Nether Brick</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="nether bricks" data-category="nether &amp; end blocks" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbricks.png" alt="" loading="lazy"></span></td>
<td>Nether Bricks</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="end stone" data-category="nether &amp; end blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/endstone.png" alt="" loading="lazy"></span></td>
<td>End Stone</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="purpur block" data-category="nether &amp; end blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/purpurblock.png" alt="" loading="lazy"></span></td>
<td>Purpur Block</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="end rod" data-category="nether &amp; end blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/endrod.png" alt="" loading="lazy"></span></td>
<td>End Rod</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="sea lantern" data-category="nether &amp; end blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/sealantern.png" alt="" loading="lazy"></span></td>
<td>Sea Lantern</td>
<td>Nether &amp; End Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="heart of the sea" data-category="rare / loot items" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/heartofthesea.png" alt="" loading="lazy"></span></td>
<td>Heart of the Sea</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="nautilus shell" data-category="rare / loot items" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/nautilusshell.png" alt="" loading="lazy"></span></td>
<td>Nautilus Shell</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="saddle" data-category="rare / loot items" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/saddle.png" alt="" loading="lazy"></span></td>
<td>Saddle</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="name tag" data-category="rare / loot items" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/nametag.png" alt="" loading="lazy"></span></td>
<td>Name Tag</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="elytra" data-category="rare / loot items" data-price="200">
<td><span class="sp-icon"><img src="/assets/items/sell/elytra.png" alt="" loading="lazy"></span></td>
<td>Elytra</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$200.00</td>
</tr>
<tr data-name="dragon egg" data-category="rare / loot items" data-price="1000">
<td><span class="sp-icon"><img src="/assets/items/sell/dragonegg.png" alt="" loading="lazy"></span></td>
<td>Dragon Egg</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$1000.00</td>
</tr>
<tr data-name="enchanted golden apple" data-category="rare / loot items" data-price="300">
<td><span class="sp-icon"><img src="/assets/items/sell/enchantedgoldenapple.png" alt="" loading="lazy"></span></td>
<td>Enchanted Golden Apple</td>
<td>Rare / Loot Items</td>
<td class="sp-price">$300.00</td>
</tr>
<tr data-name="tnt" data-category="crafted explosives" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/tnt.png" alt="" loading="lazy"></span></td>
<td>Tnt</td>
<td>Crafted Explosives</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="white wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/whitewool.png" alt="" loading="lazy"></span></td>
<td>White Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="orange wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/orangewool.png" alt="" loading="lazy"></span></td>
<td>Orange Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="magenta wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/magentawool.png" alt="" loading="lazy"></span></td>
<td>Magenta Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light blue wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluewool.png" alt="" loading="lazy"></span></td>
<td>Light Blue Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="yellow wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowwool.png" alt="" loading="lazy"></span></td>
<td>Yellow Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="lime wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/limewool.png" alt="" loading="lazy"></span></td>
<td>Lime Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="pink wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkwool.png" alt="" loading="lazy"></span></td>
<td>Pink Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="gray wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/graywool.png" alt="" loading="lazy"></span></td>
<td>Gray Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light gray wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraywool.png" alt="" loading="lazy"></span></td>
<td>Light Gray Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cyan wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanwool.png" alt="" loading="lazy"></span></td>
<td>Cyan Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="purple wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/purplewool.png" alt="" loading="lazy"></span></td>
<td>Purple Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="blue wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/bluewool.png" alt="" loading="lazy"></span></td>
<td>Blue Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="brown wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/brownwool.png" alt="" loading="lazy"></span></td>
<td>Brown Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="green wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/greenwool.png" alt="" loading="lazy"></span></td>
<td>Green Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="red wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redwool.png" alt="" loading="lazy"></span></td>
<td>Red Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="black wool" data-category="wool &amp; dyes" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blackwool.png" alt="" loading="lazy"></span></td>
<td>Black Wool</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="white dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/whitedye.png" alt="" loading="lazy"></span></td>
<td>White Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="orange dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/orangedye.png" alt="" loading="lazy"></span></td>
<td>Orange Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="magenta dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/magentadye.png" alt="" loading="lazy"></span></td>
<td>Magenta Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="light blue dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluedye.png" alt="" loading="lazy"></span></td>
<td>Light Blue Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="yellow dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowdye.png" alt="" loading="lazy"></span></td>
<td>Yellow Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="lime dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/limedye.png" alt="" loading="lazy"></span></td>
<td>Lime Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="pink dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkdye.png" alt="" loading="lazy"></span></td>
<td>Pink Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="gray dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/graydye.png" alt="" loading="lazy"></span></td>
<td>Gray Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="light gray dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraydye.png" alt="" loading="lazy"></span></td>
<td>Light Gray Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cyan dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/cyandye.png" alt="" loading="lazy"></span></td>
<td>Cyan Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="purple dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/purpledye.png" alt="" loading="lazy"></span></td>
<td>Purple Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="blue dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/bluedye.png" alt="" loading="lazy"></span></td>
<td>Blue Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="brown dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/browndye.png" alt="" loading="lazy"></span></td>
<td>Brown Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="green dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/greendye.png" alt="" loading="lazy"></span></td>
<td>Green Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="red dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/reddye.png" alt="" loading="lazy"></span></td>
<td>Red Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="black dye" data-category="wool &amp; dyes" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/blackdye.png" alt="" loading="lazy"></span></td>
<td>Black Dye</td>
<td>Wool &amp; Dyes</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="coal ore" data-category="ores &amp; raw materials" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/coalore.png" alt="" loading="lazy"></span></td>
<td>Coal Ore</td>
<td>Ores &amp; Raw Materials</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="copper nugget" data-category="ores &amp; raw materials" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/coppernugget.png" alt="" loading="lazy"></span></td>
<td>Copper Nugget</td>
<td>Ores &amp; Raw Materials</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="deepslate coal ore" data-category="ores &amp; raw materials" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatecoalore.png" alt="" loading="lazy"></span></td>
<td>Deepslate Coal Ore</td>
<td>Ores &amp; Raw Materials</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/copperbars.png" alt="" loading="lazy"></span></td>
<td>Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/copperbulb.png" alt="" loading="lazy"></span></td>
<td>Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/copperchain.png" alt="" loading="lazy"></span></td>
<td>Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/copperdoor.png" alt="" loading="lazy"></span></td>
<td>Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/coppergrate.png" alt="" loading="lazy"></span></td>
<td>Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/copperlantern.png" alt="" loading="lazy"></span></td>
<td>Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="copper torch" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/coppertorch.png" alt="" loading="lazy"></span></td>
<td>Copper Torch</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/coppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cutcopper.png" alt="" loading="lazy"></span></td>
<td>Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/cutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Exposed Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopper.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopperbars.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="exposed copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="exposed copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopperchain.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="exposed copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Exposed Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="exposed copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="exposed copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Exposed Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="exposed copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="exposed copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Exposed Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="exposed cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcutcopper.png" alt="" loading="lazy"></span></td>
<td>Exposed Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Exposed Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="exposed cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Exposed Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="exposed lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/exposedlightningrod.png" alt="" loading="lazy"></span></td>
<td>Exposed Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/lightningrod.png" alt="" loading="lazy"></span></td>
<td>Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="oxidized chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Oxidized Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="oxidized copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopper.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="oxidized copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopperbars.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="oxidized copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="oxidized copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopperchain.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="oxidized copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Oxidized Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="oxidized copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="oxidized copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Oxidized Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="oxidized copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="oxidized copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="oxidized copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Oxidized Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="oxidized cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcutcopper.png" alt="" loading="lazy"></span></td>
<td>Oxidized Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="oxidized cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Oxidized Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="oxidized cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Oxidized Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="oxidized lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/oxidizedlightningrod.png" alt="" loading="lazy"></span></td>
<td>Oxidized Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperbars.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="waxed copper block" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperblock.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Block</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperchain.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="waxed copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="waxed cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcutcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Waxed Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="waxed cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Waxed Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopperbars.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="waxed exposed copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed exposed copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopperchain.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed exposed copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Exposed Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed exposed copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed exposed copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Exposed Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="waxed exposed copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed exposed copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="waxed exposed cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcutcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="waxed exposed cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed exposed lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedexposedlightningrod.png" alt="" loading="lazy"></span></td>
<td>Waxed Exposed Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedlightningrod.png" alt="" loading="lazy"></span></td>
<td>Waxed Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed oxidized chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed oxidized copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed oxidized copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopperbars.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="waxed oxidized copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed oxidized copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopperchain.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed oxidized copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Oxidized Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed oxidized copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed oxidized copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Oxidized Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="waxed oxidized copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed oxidized copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed oxidized copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="waxed oxidized cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcutcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed oxidized cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="waxed oxidized cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed oxidized lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedoxidizedlightningrod.png" alt="" loading="lazy"></span></td>
<td>Waxed Oxidized Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed weathered chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed weathered copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed weathered copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopperbars.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="waxed weathered copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="waxed weathered copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopperchain.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed weathered copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Weathered Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed weathered copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="waxed weathered copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Waxed Weathered Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="waxed weathered copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed weathered copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="waxed weathered copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="waxed weathered cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcutcopper.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed weathered cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="waxed weathered cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="waxed weathered lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/waxedweatheredlightningrod.png" alt="" loading="lazy"></span></td>
<td>Waxed Weathered Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="weathered chiseled copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredchiseledcopper.png" alt="" loading="lazy"></span></td>
<td>Weathered Chiseled Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="weathered copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopper.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="weathered copper bars" data-category="copper blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopperbars.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Bars</td>
<td>Copper Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="weathered copper bulb" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopperbulb.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Bulb</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="weathered copper chain" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopperchain.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Chain</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="weathered copper chest" data-category="copper blocks" data-price="3">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Weathered Copper Chest</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="weathered copper door" data-category="copper blocks" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopperdoor.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Door</td>
<td>Copper Blocks</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="weathered copper golem statue" data-category="copper blocks" data-price="5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Weathered Copper Golem Statue</td>
<td>Copper Blocks</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="weathered copper grate" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcoppergrate.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Grate</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="weathered copper lantern" data-category="copper blocks" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcopperlantern.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Lantern</td>
<td>Copper Blocks</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="weathered copper trapdoor" data-category="copper blocks" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcoppertrapdoor.png" alt="" loading="lazy"></span></td>
<td>Weathered Copper Trapdoor</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="weathered cut copper" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcutcopper.png" alt="" loading="lazy"></span></td>
<td>Weathered Cut Copper</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="weathered cut copper slab" data-category="copper blocks" data-price="6.75">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcutcopperslab.png" alt="" loading="lazy"></span></td>
<td>Weathered Cut Copper Slab</td>
<td>Copper Blocks</td>
<td class="sp-price">$6.75</td>
</tr>
<tr data-name="weathered cut copper stairs" data-category="copper blocks" data-price="13.5">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredcutcopperstairs.png" alt="" loading="lazy"></span></td>
<td>Weathered Cut Copper Stairs</td>
<td>Copper Blocks</td>
<td class="sp-price">$13.50</td>
</tr>
<tr data-name="weathered lightning rod" data-category="copper blocks" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/weatheredlightningrod.png" alt="" loading="lazy"></span></td>
<td>Weathered Lightning Rod</td>
<td>Copper Blocks</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="chiseled cinnabar" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledcinnabar.png" alt="" loading="lazy"></span></td>
<td>Chiseled Cinnabar</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="chiseled resin bricks" data-category="resin, sulfur &amp; cinnabar" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledresinbricks.png" alt="" loading="lazy"></span></td>
<td>Chiseled Resin Bricks</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="chiseled sulfur" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledsulfur.png" alt="" loading="lazy"></span></td>
<td>Chiseled Sulfur</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cinnabar" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabar.png" alt="" loading="lazy"></span></td>
<td>Cinnabar</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cinnabar brick wall" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarbrickwall.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Brick Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cinnabar bricks" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarbricks.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Bricks</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cinnabar slab" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarslab.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Slab</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cinnabar stairs" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarstairs.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Stairs</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cinnabar wall" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarwall.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="polished cinnabar" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedcinnabar.png" alt="" loading="lazy"></span></td>
<td>Polished Cinnabar</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="polished cinnabar slab" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedcinnabarslab.png" alt="" loading="lazy"></span></td>
<td>Polished Cinnabar Slab</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="polished cinnabar stairs" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedcinnabarstairs.png" alt="" loading="lazy"></span></td>
<td>Polished Cinnabar Stairs</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="polished cinnabar wall" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedcinnabarwall.png" alt="" loading="lazy"></span></td>
<td>Polished Cinnabar Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="polished sulfur" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedsulfur.png" alt="" loading="lazy"></span></td>
<td>Polished Sulfur</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="polished sulfur slab" data-category="resin, sulfur &amp; cinnabar" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedsulfurslab.png" alt="" loading="lazy"></span></td>
<td>Polished Sulfur Slab</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="polished sulfur stairs" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedsulfurstairs.png" alt="" loading="lazy"></span></td>
<td>Polished Sulfur Stairs</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="polished sulfur wall" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedsulfurwall.png" alt="" loading="lazy"></span></td>
<td>Polished Sulfur Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="potent sulfur" data-category="resin, sulfur &amp; cinnabar" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/potentsulfur.png" alt="" loading="lazy"></span></td>
<td>Potent Sulfur</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="resin block" data-category="resin, sulfur &amp; cinnabar" data-price="4.5">
<td><span class="sp-icon"><img src="/assets/items/sell/resinblock.png" alt="" loading="lazy"></span></td>
<td>Resin Block</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$4.50</td>
</tr>
<tr data-name="resin brick" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/resinbrick.png" alt="" loading="lazy"></span></td>
<td>Resin Brick</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="resin brick slab" data-category="resin, sulfur &amp; cinnabar" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/resinbrickslab.png" alt="" loading="lazy"></span></td>
<td>Resin Brick Slab</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="resin brick stairs" data-category="resin, sulfur &amp; cinnabar" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/resinbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Resin Brick Stairs</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="resin brick wall" data-category="resin, sulfur &amp; cinnabar" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/resinbrickwall.png" alt="" loading="lazy"></span></td>
<td>Resin Brick Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="resin bricks" data-category="resin, sulfur &amp; cinnabar" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/resinbricks.png" alt="" loading="lazy"></span></td>
<td>Resin Bricks</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="resin clump" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/resinclump.png" alt="" loading="lazy"></span></td>
<td>Resin Clump</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfur.png" alt="" loading="lazy"></span></td>
<td>Sulfur</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur brick wall" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurbrickwall.png" alt="" loading="lazy"></span></td>
<td>Sulfur Brick Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur bricks" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurbricks.png" alt="" loading="lazy"></span></td>
<td>Sulfur Bricks</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur slab" data-category="resin, sulfur &amp; cinnabar" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurslab.png" alt="" loading="lazy"></span></td>
<td>Sulfur Slab</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="sulfur spike" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurspike.png" alt="" loading="lazy"></span></td>
<td>Sulfur Spike</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur stairs" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurstairs.png" alt="" loading="lazy"></span></td>
<td>Sulfur Stairs</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sulfur wall" data-category="resin, sulfur &amp; cinnabar" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurwall.png" alt="" loading="lazy"></span></td>
<td>Sulfur Wall</td>
<td>Resin, Sulfur &amp; Cinnabar</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="armadillo scute" data-category="mob drops" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/armadilloscute.png" alt="" loading="lazy"></span></td>
<td>Armadillo Scute</td>
<td>Mob Drops</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="arrow" data-category="mob drops" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/arrow.png" alt="" loading="lazy"></span></td>
<td>Arrow</td>
<td>Mob Drops</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="blue egg" data-category="mob drops" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/blueegg.png" alt="" loading="lazy"></span></td>
<td>Blue Egg</td>
<td>Mob Drops</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="breeze rod" data-category="mob drops" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/breezerod.png" alt="" loading="lazy"></span></td>
<td>Breeze Rod</td>
<td>Mob Drops</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="brown egg" data-category="mob drops" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/brownegg.png" alt="" loading="lazy"></span></td>
<td>Brown Egg</td>
<td>Mob Drops</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="fire charge" data-category="mob drops" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/firecharge.png" alt="" loading="lazy"></span></td>
<td>Fire Charge</td>
<td>Mob Drops</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="spectral arrow" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/spectralarrow.png" alt="" loading="lazy"></span></td>
<td>Spectral Arrow</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="turtle egg" data-category="mob drops" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/turtleegg.png" alt="" loading="lazy"></span></td>
<td>Turtle Egg</td>
<td>Mob Drops</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="wind charge" data-category="mob drops" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/windcharge.png" alt="" loading="lazy"></span></td>
<td>Wind Charge</td>
<td>Mob Drops</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="fermented spider eye" data-category="crops &amp; farm produce" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/fermentedspidereye.png" alt="" loading="lazy"></span></td>
<td>Fermented Spider Eye</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="melon seeds" data-category="crops &amp; farm produce" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/melonseeds.png" alt="" loading="lazy"></span></td>
<td>Melon Seeds</td>
<td>Crops &amp; Farm Produce</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="acacia leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/acacialeaves.png" alt="" loading="lazy"></span></td>
<td>Acacia Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="acacia sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciasapling.png" alt="" loading="lazy"></span></td>
<td>Acacia Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="acacia wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciawood.png" alt="" loading="lazy"></span></td>
<td>Acacia Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="bamboo mosaic" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboomosaic.png" alt="" loading="lazy"></span></td>
<td>Bamboo Mosaic</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="birch leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/birchleaves.png" alt="" loading="lazy"></span></td>
<td>Birch Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="birch sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/birchsapling.png" alt="" loading="lazy"></span></td>
<td>Birch Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="birch wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/birchwood.png" alt="" loading="lazy"></span></td>
<td>Birch Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cherry leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryleaves.png" alt="" loading="lazy"></span></td>
<td>Cherry Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cherry sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrysapling.png" alt="" loading="lazy"></span></td>
<td>Cherry Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="cherry wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrywood.png" alt="" loading="lazy"></span></td>
<td>Cherry Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="crimson fungus" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonfungus.png" alt="" loading="lazy"></span></td>
<td>Crimson Fungus</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="crimson hyphae" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonhyphae.png" alt="" loading="lazy"></span></td>
<td>Crimson Hyphae</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dark oak leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakleaves.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="dark oak sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoaksapling.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dark oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakwood.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="jungle leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/jungleleaves.png" alt="" loading="lazy"></span></td>
<td>Jungle Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="jungle sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/junglesapling.png" alt="" loading="lazy"></span></td>
<td>Jungle Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="jungle wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/junglewood.png" alt="" loading="lazy"></span></td>
<td>Jungle Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="mangrove leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveleaves.png" alt="" loading="lazy"></span></td>
<td>Mangrove Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="mangrove propagule" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovepropagule.png" alt="" loading="lazy"></span></td>
<td>Mangrove Propagule</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mangrove wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovewood.png" alt="" loading="lazy"></span></td>
<td>Mangrove Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="oak leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/oakleaves.png" alt="" loading="lazy"></span></td>
<td>Oak Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="oak sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/oaksapling.png" alt="" loading="lazy"></span></td>
<td>Oak Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/oakwood.png" alt="" loading="lazy"></span></td>
<td>Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pale oak leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakleaves.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="pale oak sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoaksapling.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pale oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakwood.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="spruce leaves" data-category="wood expansion" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/spruceleaves.png" alt="" loading="lazy"></span></td>
<td>Spruce Leaves</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="spruce sapling" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucesapling.png" alt="" loading="lazy"></span></td>
<td>Spruce Sapling</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="spruce wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucewood.png" alt="" loading="lazy"></span></td>
<td>Spruce Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped acacia log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedacacialog.png" alt="" loading="lazy"></span></td>
<td>Stripped Acacia Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped acacia wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedacaciawood.png" alt="" loading="lazy"></span></td>
<td>Stripped Acacia Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped bamboo block" data-category="wood expansion" data-price="0.9">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedbambooblock.png" alt="" loading="lazy"></span></td>
<td>Stripped Bamboo Block</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.90</td>
</tr>
<tr data-name="stripped birch log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedbirchlog.png" alt="" loading="lazy"></span></td>
<td>Stripped Birch Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped birch wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedbirchwood.png" alt="" loading="lazy"></span></td>
<td>Stripped Birch Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped cherry log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedcherrylog.png" alt="" loading="lazy"></span></td>
<td>Stripped Cherry Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped cherry wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedcherrywood.png" alt="" loading="lazy"></span></td>
<td>Stripped Cherry Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped crimson hyphae" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedcrimsonhyphae.png" alt="" loading="lazy"></span></td>
<td>Stripped Crimson Hyphae</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped crimson stem" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedcrimsonstem.png" alt="" loading="lazy"></span></td>
<td>Stripped Crimson Stem</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped dark oak log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippeddarkoaklog.png" alt="" loading="lazy"></span></td>
<td>Stripped Dark Oak Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped dark oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippeddarkoakwood.png" alt="" loading="lazy"></span></td>
<td>Stripped Dark Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped jungle log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedjunglelog.png" alt="" loading="lazy"></span></td>
<td>Stripped Jungle Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped jungle wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedjunglewood.png" alt="" loading="lazy"></span></td>
<td>Stripped Jungle Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped mangrove log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedmangrovelog.png" alt="" loading="lazy"></span></td>
<td>Stripped Mangrove Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped mangrove wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedmangrovewood.png" alt="" loading="lazy"></span></td>
<td>Stripped Mangrove Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped oak log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedoaklog.png" alt="" loading="lazy"></span></td>
<td>Stripped Oak Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedoakwood.png" alt="" loading="lazy"></span></td>
<td>Stripped Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped pale oak log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedpaleoaklog.png" alt="" loading="lazy"></span></td>
<td>Stripped Pale Oak Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped pale oak wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedpaleoakwood.png" alt="" loading="lazy"></span></td>
<td>Stripped Pale Oak Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped spruce log" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedsprucelog.png" alt="" loading="lazy"></span></td>
<td>Stripped Spruce Log</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped spruce wood" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedsprucewood.png" alt="" loading="lazy"></span></td>
<td>Stripped Spruce Wood</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped warped hyphae" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedwarpedhyphae.png" alt="" loading="lazy"></span></td>
<td>Stripped Warped Hyphae</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="stripped warped stem" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/strippedwarpedstem.png" alt="" loading="lazy"></span></td>
<td>Stripped Warped Stem</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="warped fungus" data-category="wood expansion" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedfungus.png" alt="" loading="lazy"></span></td>
<td>Warped Fungus</td>
<td>Wood Expansion</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped hyphae" data-category="wood expansion" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedhyphae.png" alt="" loading="lazy"></span></td>
<td>Warped Hyphae</td>
<td>Wood Expansion</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="acacia boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciaboat.png" alt="" loading="lazy"></span></td>
<td>Acacia Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="acacia button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciabutton.png" alt="" loading="lazy"></span></td>
<td>Acacia Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="acacia chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciachestboat.png" alt="" loading="lazy"></span></td>
<td>Acacia Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="acacia door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciadoor.png" alt="" loading="lazy"></span></td>
<td>Acacia Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="acacia fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciafence.png" alt="" loading="lazy"></span></td>
<td>Acacia Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="acacia fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciafencegate.png" alt="" loading="lazy"></span></td>
<td>Acacia Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="acacia hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciahangingsign.png" alt="" loading="lazy"></span></td>
<td>Acacia Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="acacia pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciapressureplate.png" alt="" loading="lazy"></span></td>
<td>Acacia Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="acacia shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciashelf.png" alt="" loading="lazy"></span></td>
<td>Acacia Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="acacia sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciasign.png" alt="" loading="lazy"></span></td>
<td>Acacia Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="acacia slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciaslab.png" alt="" loading="lazy"></span></td>
<td>Acacia Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="acacia stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciastairs.png" alt="" loading="lazy"></span></td>
<td>Acacia Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="acacia trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/acaciatrapdoor.png" alt="" loading="lazy"></span></td>
<td>Acacia Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="bamboo button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboobutton.png" alt="" loading="lazy"></span></td>
<td>Bamboo Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="bamboo chest raft" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboochestraft.png" alt="" loading="lazy"></span></td>
<td>Bamboo Chest Raft</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="bamboo door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboodoor.png" alt="" loading="lazy"></span></td>
<td>Bamboo Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="bamboo fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboofence.png" alt="" loading="lazy"></span></td>
<td>Bamboo Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="bamboo fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboofencegate.png" alt="" loading="lazy"></span></td>
<td>Bamboo Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="bamboo hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboohangingsign.png" alt="" loading="lazy"></span></td>
<td>Bamboo Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="bamboo mosaic slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboomosaicslab.png" alt="" loading="lazy"></span></td>
<td>Bamboo Mosaic Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="bamboo mosaic stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboomosaicstairs.png" alt="" loading="lazy"></span></td>
<td>Bamboo Mosaic Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="bamboo pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboopressureplate.png" alt="" loading="lazy"></span></td>
<td>Bamboo Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="bamboo raft" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/bambooraft.png" alt="" loading="lazy"></span></td>
<td>Bamboo Raft</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="bamboo shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/bambooshelf.png" alt="" loading="lazy"></span></td>
<td>Bamboo Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="bamboo sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboosign.png" alt="" loading="lazy"></span></td>
<td>Bamboo Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="bamboo slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/bambooslab.png" alt="" loading="lazy"></span></td>
<td>Bamboo Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="bamboo stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/bamboostairs.png" alt="" loading="lazy"></span></td>
<td>Bamboo Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="bamboo trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/bambootrapdoor.png" alt="" loading="lazy"></span></td>
<td>Bamboo Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="birch boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/birchboat.png" alt="" loading="lazy"></span></td>
<td>Birch Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="birch button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/birchbutton.png" alt="" loading="lazy"></span></td>
<td>Birch Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="birch chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/birchchestboat.png" alt="" loading="lazy"></span></td>
<td>Birch Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="birch door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/birchdoor.png" alt="" loading="lazy"></span></td>
<td>Birch Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="birch fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/birchfence.png" alt="" loading="lazy"></span></td>
<td>Birch Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="birch fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/birchfencegate.png" alt="" loading="lazy"></span></td>
<td>Birch Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="birch hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/birchhangingsign.png" alt="" loading="lazy"></span></td>
<td>Birch Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="birch pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/birchpressureplate.png" alt="" loading="lazy"></span></td>
<td>Birch Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="birch shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/birchshelf.png" alt="" loading="lazy"></span></td>
<td>Birch Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="birch sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/birchsign.png" alt="" loading="lazy"></span></td>
<td>Birch Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="birch slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/birchslab.png" alt="" loading="lazy"></span></td>
<td>Birch Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="birch stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/birchstairs.png" alt="" loading="lazy"></span></td>
<td>Birch Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="birch trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/birchtrapdoor.png" alt="" loading="lazy"></span></td>
<td>Birch Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="cherry boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryboat.png" alt="" loading="lazy"></span></td>
<td>Cherry Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="cherry button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrybutton.png" alt="" loading="lazy"></span></td>
<td>Cherry Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cherry chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrychestboat.png" alt="" loading="lazy"></span></td>
<td>Cherry Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="cherry door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrydoor.png" alt="" loading="lazy"></span></td>
<td>Cherry Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cherry fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryfence.png" alt="" loading="lazy"></span></td>
<td>Cherry Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="cherry fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryfencegate.png" alt="" loading="lazy"></span></td>
<td>Cherry Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cherry hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryhangingsign.png" alt="" loading="lazy"></span></td>
<td>Cherry Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cherry pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrypressureplate.png" alt="" loading="lazy"></span></td>
<td>Cherry Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="cherry shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryshelf.png" alt="" loading="lazy"></span></td>
<td>Cherry Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cherry sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrysign.png" alt="" loading="lazy"></span></td>
<td>Cherry Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="cherry slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cherryslab.png" alt="" loading="lazy"></span></td>
<td>Cherry Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cherry stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrystairs.png" alt="" loading="lazy"></span></td>
<td>Cherry Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cherry trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/cherrytrapdoor.png" alt="" loading="lazy"></span></td>
<td>Cherry Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="crimson button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonbutton.png" alt="" loading="lazy"></span></td>
<td>Crimson Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="crimson door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsondoor.png" alt="" loading="lazy"></span></td>
<td>Crimson Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="crimson fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonfence.png" alt="" loading="lazy"></span></td>
<td>Crimson Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="crimson fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonfencegate.png" alt="" loading="lazy"></span></td>
<td>Crimson Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="crimson hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonhangingsign.png" alt="" loading="lazy"></span></td>
<td>Crimson Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="crimson pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonpressureplate.png" alt="" loading="lazy"></span></td>
<td>Crimson Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="crimson shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonshelf.png" alt="" loading="lazy"></span></td>
<td>Crimson Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="crimson sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonsign.png" alt="" loading="lazy"></span></td>
<td>Crimson Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="crimson slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonslab.png" alt="" loading="lazy"></span></td>
<td>Crimson Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="crimson stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonstairs.png" alt="" loading="lazy"></span></td>
<td>Crimson Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="crimson trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsontrapdoor.png" alt="" loading="lazy"></span></td>
<td>Crimson Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="dark oak boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakboat.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="dark oak button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakbutton.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="dark oak chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakchestboat.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="dark oak door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakdoor.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="dark oak fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakfence.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="dark oak fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakfencegate.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dark oak hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakhangingsign.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="dark oak pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakpressureplate.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dark oak shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakshelf.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dark oak sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoaksign.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="dark oak slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakslab.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="dark oak stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoakstairs.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="dark oak trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/darkoaktrapdoor.png" alt="" loading="lazy"></span></td>
<td>Dark Oak Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="jungle boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/jungleboat.png" alt="" loading="lazy"></span></td>
<td>Jungle Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="jungle button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/junglebutton.png" alt="" loading="lazy"></span></td>
<td>Jungle Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="jungle chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/junglechestboat.png" alt="" loading="lazy"></span></td>
<td>Jungle Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="jungle door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/jungledoor.png" alt="" loading="lazy"></span></td>
<td>Jungle Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="jungle fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/junglefence.png" alt="" loading="lazy"></span></td>
<td>Jungle Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="jungle fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/junglefencegate.png" alt="" loading="lazy"></span></td>
<td>Jungle Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="jungle hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/junglehangingsign.png" alt="" loading="lazy"></span></td>
<td>Jungle Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="jungle pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/junglepressureplate.png" alt="" loading="lazy"></span></td>
<td>Jungle Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="jungle shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/jungleshelf.png" alt="" loading="lazy"></span></td>
<td>Jungle Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="jungle sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/junglesign.png" alt="" loading="lazy"></span></td>
<td>Jungle Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="jungle slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/jungleslab.png" alt="" loading="lazy"></span></td>
<td>Jungle Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="jungle stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/junglestairs.png" alt="" loading="lazy"></span></td>
<td>Jungle Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="jungle trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/jungletrapdoor.png" alt="" loading="lazy"></span></td>
<td>Jungle Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="mangrove boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveboat.png" alt="" loading="lazy"></span></td>
<td>Mangrove Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="mangrove button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovebutton.png" alt="" loading="lazy"></span></td>
<td>Mangrove Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="mangrove chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovechestboat.png" alt="" loading="lazy"></span></td>
<td>Mangrove Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="mangrove door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovedoor.png" alt="" loading="lazy"></span></td>
<td>Mangrove Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="mangrove fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovefence.png" alt="" loading="lazy"></span></td>
<td>Mangrove Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="mangrove fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovefencegate.png" alt="" loading="lazy"></span></td>
<td>Mangrove Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="mangrove hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovehangingsign.png" alt="" loading="lazy"></span></td>
<td>Mangrove Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="mangrove pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovepressureplate.png" alt="" loading="lazy"></span></td>
<td>Mangrove Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mangrove shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveshelf.png" alt="" loading="lazy"></span></td>
<td>Mangrove Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="mangrove sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovesign.png" alt="" loading="lazy"></span></td>
<td>Mangrove Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="mangrove slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveslab.png" alt="" loading="lazy"></span></td>
<td>Mangrove Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mangrove stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovestairs.png" alt="" loading="lazy"></span></td>
<td>Mangrove Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="mangrove trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/mangrovetrapdoor.png" alt="" loading="lazy"></span></td>
<td>Mangrove Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="oak boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/oakboat.png" alt="" loading="lazy"></span></td>
<td>Oak Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="oak button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/oakbutton.png" alt="" loading="lazy"></span></td>
<td>Oak Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="oak chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/oakchestboat.png" alt="" loading="lazy"></span></td>
<td>Oak Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="oak door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/oakdoor.png" alt="" loading="lazy"></span></td>
<td>Oak Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="oak fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/oakfence.png" alt="" loading="lazy"></span></td>
<td>Oak Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="oak fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/oakfencegate.png" alt="" loading="lazy"></span></td>
<td>Oak Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="oak hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/oakhangingsign.png" alt="" loading="lazy"></span></td>
<td>Oak Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="oak pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/oakpressureplate.png" alt="" loading="lazy"></span></td>
<td>Oak Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="oak shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/oakshelf.png" alt="" loading="lazy"></span></td>
<td>Oak Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="oak sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/oaksign.png" alt="" loading="lazy"></span></td>
<td>Oak Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="oak slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/oakslab.png" alt="" loading="lazy"></span></td>
<td>Oak Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="oak stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/oakstairs.png" alt="" loading="lazy"></span></td>
<td>Oak Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="oak trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/oaktrapdoor.png" alt="" loading="lazy"></span></td>
<td>Oak Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="pale oak boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakboat.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="pale oak button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakbutton.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="pale oak chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakchestboat.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="pale oak door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakdoor.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="pale oak fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakfence.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="pale oak fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakfencegate.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="pale oak hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakhangingsign.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="pale oak pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakpressureplate.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pale oak shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakshelf.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pale oak sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoaksign.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="pale oak slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakslab.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="pale oak stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoakstairs.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pale oak trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/paleoaktrapdoor.png" alt="" loading="lazy"></span></td>
<td>Pale Oak Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="spruce boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/spruceboat.png" alt="" loading="lazy"></span></td>
<td>Spruce Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="spruce button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucebutton.png" alt="" loading="lazy"></span></td>
<td>Spruce Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="spruce chest boat" data-category="wood building parts" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucechestboat.png" alt="" loading="lazy"></span></td>
<td>Spruce Chest Boat</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="spruce door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucedoor.png" alt="" loading="lazy"></span></td>
<td>Spruce Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="spruce fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucefence.png" alt="" loading="lazy"></span></td>
<td>Spruce Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="spruce fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucefencegate.png" alt="" loading="lazy"></span></td>
<td>Spruce Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="spruce hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucehangingsign.png" alt="" loading="lazy"></span></td>
<td>Spruce Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="spruce pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucepressureplate.png" alt="" loading="lazy"></span></td>
<td>Spruce Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="spruce shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/spruceshelf.png" alt="" loading="lazy"></span></td>
<td>Spruce Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="spruce sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucesign.png" alt="" loading="lazy"></span></td>
<td>Spruce Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="spruce slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/spruceslab.png" alt="" loading="lazy"></span></td>
<td>Spruce Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="spruce stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucestairs.png" alt="" loading="lazy"></span></td>
<td>Spruce Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="spruce trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/sprucetrapdoor.png" alt="" loading="lazy"></span></td>
<td>Spruce Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="warped button" data-category="wood building parts" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedbutton.png" alt="" loading="lazy"></span></td>
<td>Warped Button</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="warped door" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/warpeddoor.png" alt="" loading="lazy"></span></td>
<td>Warped Door</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="warped fence" data-category="wood building parts" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedfence.png" alt="" loading="lazy"></span></td>
<td>Warped Fence</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="warped fence gate" data-category="wood building parts" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedfencegate.png" alt="" loading="lazy"></span></td>
<td>Warped Fence Gate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="warped hanging sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedhangingsign.png" alt="" loading="lazy"></span></td>
<td>Warped Hanging Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="warped pressure plate" data-category="wood building parts" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedpressureplate.png" alt="" loading="lazy"></span></td>
<td>Warped Pressure Plate</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped shelf" data-category="wood building parts" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedshelf.png" alt="" loading="lazy"></span></td>
<td>Warped Shelf</td>
<td>Wood Building Parts</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="warped sign" data-category="wood building parts" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedsign.png" alt="" loading="lazy"></span></td>
<td>Warped Sign</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="warped slab" data-category="wood building parts" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedslab.png" alt="" loading="lazy"></span></td>
<td>Warped Slab</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="warped stairs" data-category="wood building parts" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedstairs.png" alt="" loading="lazy"></span></td>
<td>Warped Stairs</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="warped trapdoor" data-category="wood building parts" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedtrapdoor.png" alt="" loading="lazy"></span></td>
<td>Warped Trapdoor</td>
<td>Wood Building Parts</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="amethyst cluster" data-category="stone variants" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/amethystcluster.png" alt="" loading="lazy"></span></td>
<td>Amethyst Cluster</td>
<td>Stone Variants</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="andesite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/andesiteslab.png" alt="" loading="lazy"></span></td>
<td>Andesite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="andesite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/andesitestairs.png" alt="" loading="lazy"></span></td>
<td>Andesite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="andesite wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/andesitewall.png" alt="" loading="lazy"></span></td>
<td>Andesite Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="blackstone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstoneslab.png" alt="" loading="lazy"></span></td>
<td>Blackstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="blackstone stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstonestairs.png" alt="" loading="lazy"></span></td>
<td>Blackstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="blackstone wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstonewall.png" alt="" loading="lazy"></span></td>
<td>Blackstone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="brick slab" data-category="stone variants" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/brickslab.png" alt="" loading="lazy"></span></td>
<td>Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="brick stairs" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/brickstairs.png" alt="" loading="lazy"></span></td>
<td>Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="brick wall" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/brickwall.png" alt="" loading="lazy"></span></td>
<td>Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="calibrated sculk sensor" data-category="stone variants" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/calibratedsculksensor.png" alt="" loading="lazy"></span></td>
<td>Calibrated Sculk Sensor</td>
<td>Stone Variants</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="chiseled deepslate" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseleddeepslate.png" alt="" loading="lazy"></span></td>
<td>Chiseled Deepslate</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="chiseled nether bricks" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/chiselednetherbricks.png" alt="" loading="lazy"></span></td>
<td>Chiseled Nether Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="chiseled polished blackstone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledpolishedblackstone.png" alt="" loading="lazy"></span></td>
<td>Chiseled Polished Blackstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="chiseled quartz block" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledquartzblock.png" alt="" loading="lazy"></span></td>
<td>Chiseled Quartz Block</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="chiseled red sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledredsandstone.png" alt="" loading="lazy"></span></td>
<td>Chiseled Red Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="chiseled sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledsandstone.png" alt="" loading="lazy"></span></td>
<td>Chiseled Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="chiseled stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledstonebricks.png" alt="" loading="lazy"></span></td>
<td>Chiseled Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="chiseled tuff" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledtuff.png" alt="" loading="lazy"></span></td>
<td>Chiseled Tuff</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="chiseled tuff bricks" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledtuffbricks.png" alt="" loading="lazy"></span></td>
<td>Chiseled Tuff Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="cinnabar brick slab" data-category="stone variants" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarbrickslab.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="cinnabar brick stairs" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cinnabarbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Cinnabar Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="cobbled deepslate slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cobbleddeepslateslab.png" alt="" loading="lazy"></span></td>
<td>Cobbled Deepslate Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cobbled deepslate stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cobbleddeepslatestairs.png" alt="" loading="lazy"></span></td>
<td>Cobbled Deepslate Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cobbled deepslate wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cobbleddeepslatewall.png" alt="" loading="lazy"></span></td>
<td>Cobbled Deepslate Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cobblestone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/cobblestoneslab.png" alt="" loading="lazy"></span></td>
<td>Cobblestone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="cobblestone stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cobblestonestairs.png" alt="" loading="lazy"></span></td>
<td>Cobblestone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cobblestone wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cobblestonewall.png" alt="" loading="lazy"></span></td>
<td>Cobblestone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cobweb" data-category="stone variants" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cobweb.png" alt="" loading="lazy"></span></td>
<td>Cobweb</td>
<td>Stone Variants</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cracked deepslate bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/crackeddeepslatebricks.png" alt="" loading="lazy"></span></td>
<td>Cracked Deepslate Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cracked deepslate tiles" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/crackeddeepslatetiles.png" alt="" loading="lazy"></span></td>
<td>Cracked Deepslate Tiles</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cracked nether bricks" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/crackednetherbricks.png" alt="" loading="lazy"></span></td>
<td>Cracked Nether Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="cracked polished blackstone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/crackedpolishedblackstonebricks.png" alt="" loading="lazy"></span></td>
<td>Cracked Polished Blackstone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cracked stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/crackedstonebricks.png" alt="" loading="lazy"></span></td>
<td>Cracked Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cut red sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cutredsandstone.png" alt="" loading="lazy"></span></td>
<td>Cut Red Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cut red sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/cutredsandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Cut Red Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="cut sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cutsandstone.png" alt="" loading="lazy"></span></td>
<td>Cut Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cut sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/cutsandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Cut Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="dark prismarine" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkprismarine.png" alt="" loading="lazy"></span></td>
<td>Dark Prismarine</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dark prismarine slab" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/darkprismarineslab.png" alt="" loading="lazy"></span></td>
<td>Dark Prismarine Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dark prismarine stairs" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/darkprismarinestairs.png" alt="" loading="lazy"></span></td>
<td>Dark Prismarine Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="deepslate brick slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatebrickslab.png" alt="" loading="lazy"></span></td>
<td>Deepslate Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="deepslate brick stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatebrickstairs.png" alt="" loading="lazy"></span></td>
<td>Deepslate Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate brick wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatebrickwall.png" alt="" loading="lazy"></span></td>
<td>Deepslate Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatebricks.png" alt="" loading="lazy"></span></td>
<td>Deepslate Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate tile slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatetileslab.png" alt="" loading="lazy"></span></td>
<td>Deepslate Tile Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="deepslate tile stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatetilestairs.png" alt="" loading="lazy"></span></td>
<td>Deepslate Tile Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate tile wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatetilewall.png" alt="" loading="lazy"></span></td>
<td>Deepslate Tile Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="deepslate tiles" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/deepslatetiles.png" alt="" loading="lazy"></span></td>
<td>Deepslate Tiles</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="diorite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/dioriteslab.png" alt="" loading="lazy"></span></td>
<td>Diorite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="diorite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/dioritestairs.png" alt="" loading="lazy"></span></td>
<td>Diorite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="diorite wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/dioritewall.png" alt="" loading="lazy"></span></td>
<td>Diorite Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="end stone brick slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/endstonebrickslab.png" alt="" loading="lazy"></span></td>
<td>End Stone Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="end stone brick stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/endstonebrickstairs.png" alt="" loading="lazy"></span></td>
<td>End Stone Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="end stone brick wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/endstonebrickwall.png" alt="" loading="lazy"></span></td>
<td>End Stone Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="end stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/endstonebricks.png" alt="" loading="lazy"></span></td>
<td>End Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="granite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/graniteslab.png" alt="" loading="lazy"></span></td>
<td>Granite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="granite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/granitestairs.png" alt="" loading="lazy"></span></td>
<td>Granite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="granite wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/granitewall.png" alt="" loading="lazy"></span></td>
<td>Granite Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="grindstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/grindstone.png" alt="" loading="lazy"></span></td>
<td>Grindstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="infested chiseled stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedchiseledstonebricks.png" alt="" loading="lazy"></span></td>
<td>Infested Chiseled Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested cobblestone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedcobblestone.png" alt="" loading="lazy"></span></td>
<td>Infested Cobblestone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested cracked stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedcrackedstonebricks.png" alt="" loading="lazy"></span></td>
<td>Infested Cracked Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested deepslate" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infesteddeepslate.png" alt="" loading="lazy"></span></td>
<td>Infested Deepslate</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested mossy stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedmossystonebricks.png" alt="" loading="lazy"></span></td>
<td>Infested Mossy Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested stone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedstone.png" alt="" loading="lazy"></span></td>
<td>Infested Stone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="infested stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/infestedstonebricks.png" alt="" loading="lazy"></span></td>
<td>Infested Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="large amethyst bud" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/largeamethystbud.png" alt="" loading="lazy"></span></td>
<td>Large Amethyst Bud</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="medium amethyst bud" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/mediumamethystbud.png" alt="" loading="lazy"></span></td>
<td>Medium Amethyst Bud</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="mossy cobblestone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossycobblestone.png" alt="" loading="lazy"></span></td>
<td>Mossy Cobblestone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mossy cobblestone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/mossycobblestoneslab.png" alt="" loading="lazy"></span></td>
<td>Mossy Cobblestone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="mossy cobblestone stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossycobblestonestairs.png" alt="" loading="lazy"></span></td>
<td>Mossy Cobblestone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mossy cobblestone wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossycobblestonewall.png" alt="" loading="lazy"></span></td>
<td>Mossy Cobblestone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mossy stone brick slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/mossystonebrickslab.png" alt="" loading="lazy"></span></td>
<td>Mossy Stone Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="mossy stone brick stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossystonebrickstairs.png" alt="" loading="lazy"></span></td>
<td>Mossy Stone Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mossy stone brick wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossystonebrickwall.png" alt="" loading="lazy"></span></td>
<td>Mossy Stone Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mossy stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mossystonebricks.png" alt="" loading="lazy"></span></td>
<td>Mossy Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mud brick slab" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/mudbrickslab.png" alt="" loading="lazy"></span></td>
<td>Mud Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="mud brick stairs" data-category="stone variants" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mudbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Mud Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mud brick wall" data-category="stone variants" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mudbrickwall.png" alt="" loading="lazy"></span></td>
<td>Mud Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mud bricks" data-category="stone variants" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mudbricks.png" alt="" loading="lazy"></span></td>
<td>Mud Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="nether brick fence" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbrickfence.png" alt="" loading="lazy"></span></td>
<td>Nether Brick Fence</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="nether brick slab" data-category="stone variants" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbrickslab.png" alt="" loading="lazy"></span></td>
<td>Nether Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="nether brick stairs" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Nether Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="nether brick wall" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/netherbrickwall.png" alt="" loading="lazy"></span></td>
<td>Nether Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="packed mud" data-category="stone variants" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/packedmud.png" alt="" loading="lazy"></span></td>
<td>Packed Mud</td>
<td>Stone Variants</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="polished andesite" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedandesite.png" alt="" loading="lazy"></span></td>
<td>Polished Andesite</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished andesite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedandesiteslab.png" alt="" loading="lazy"></span></td>
<td>Polished Andesite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished andesite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedandesitestairs.png" alt="" loading="lazy"></span></td>
<td>Polished Andesite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished basalt" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedbasalt.png" alt="" loading="lazy"></span></td>
<td>Polished Basalt</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstone.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone brick slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonebrickslab.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished blackstone brick stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonebrickstairs.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone brick wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonebrickwall.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonebricks.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone button" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonebutton.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Button</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone pressure plate" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonepressureplate.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Pressure Plate</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstoneslab.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished blackstone stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonestairs.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished blackstone wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedblackstonewall.png" alt="" loading="lazy"></span></td>
<td>Polished Blackstone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished deepslate" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddeepslate.png" alt="" loading="lazy"></span></td>
<td>Polished Deepslate</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished deepslate slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddeepslateslab.png" alt="" loading="lazy"></span></td>
<td>Polished Deepslate Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished deepslate stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddeepslatestairs.png" alt="" loading="lazy"></span></td>
<td>Polished Deepslate Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished deepslate wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddeepslatewall.png" alt="" loading="lazy"></span></td>
<td>Polished Deepslate Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished diorite" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddiorite.png" alt="" loading="lazy"></span></td>
<td>Polished Diorite</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished diorite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddioriteslab.png" alt="" loading="lazy"></span></td>
<td>Polished Diorite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished diorite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polisheddioritestairs.png" alt="" loading="lazy"></span></td>
<td>Polished Diorite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished granite" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedgranite.png" alt="" loading="lazy"></span></td>
<td>Polished Granite</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished granite slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedgraniteslab.png" alt="" loading="lazy"></span></td>
<td>Polished Granite Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished granite stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedgranitestairs.png" alt="" loading="lazy"></span></td>
<td>Polished Granite Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished tuff" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedtuff.png" alt="" loading="lazy"></span></td>
<td>Polished Tuff</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished tuff slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedtuffslab.png" alt="" loading="lazy"></span></td>
<td>Polished Tuff Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="polished tuff stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedtuffstairs.png" alt="" loading="lazy"></span></td>
<td>Polished Tuff Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="polished tuff wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/polishedtuffwall.png" alt="" loading="lazy"></span></td>
<td>Polished Tuff Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="prismarine" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarine.png" alt="" loading="lazy"></span></td>
<td>Prismarine</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="prismarine brick slab" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinebrickslab.png" alt="" loading="lazy"></span></td>
<td>Prismarine Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="prismarine brick stairs" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinebrickstairs.png" alt="" loading="lazy"></span></td>
<td>Prismarine Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="prismarine bricks" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinebricks.png" alt="" loading="lazy"></span></td>
<td>Prismarine Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="prismarine slab" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarineslab.png" alt="" loading="lazy"></span></td>
<td>Prismarine Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="prismarine stairs" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinestairs.png" alt="" loading="lazy"></span></td>
<td>Prismarine Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="prismarine wall" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/prismarinewall.png" alt="" loading="lazy"></span></td>
<td>Prismarine Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="purpur pillar" data-category="stone variants" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/purpurpillar.png" alt="" loading="lazy"></span></td>
<td>Purpur Pillar</td>
<td>Stone Variants</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="purpur slab" data-category="stone variants" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/purpurslab.png" alt="" loading="lazy"></span></td>
<td>Purpur Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="purpur stairs" data-category="stone variants" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/purpurstairs.png" alt="" loading="lazy"></span></td>
<td>Purpur Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="quartz bricks" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/quartzbricks.png" alt="" loading="lazy"></span></td>
<td>Quartz Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="quartz pillar" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/quartzpillar.png" alt="" loading="lazy"></span></td>
<td>Quartz Pillar</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="quartz slab" data-category="stone variants" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/quartzslab.png" alt="" loading="lazy"></span></td>
<td>Quartz Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="quartz stairs" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/quartzstairs.png" alt="" loading="lazy"></span></td>
<td>Quartz Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="red nether brick slab" data-category="stone variants" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/rednetherbrickslab.png" alt="" loading="lazy"></span></td>
<td>Red Nether Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="red nether brick stairs" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/rednetherbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Red Nether Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="red nether brick wall" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/rednetherbrickwall.png" alt="" loading="lazy"></span></td>
<td>Red Nether Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="red nether bricks" data-category="stone variants" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/rednetherbricks.png" alt="" loading="lazy"></span></td>
<td>Red Nether Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="red sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/redsandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Red Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="red sandstone stairs" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redsandstonestairs.png" alt="" loading="lazy"></span></td>
<td>Red Sandstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="red sandstone wall" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redsandstonewall.png" alt="" loading="lazy"></span></td>
<td>Red Sandstone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="redstone lamp" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/redstonelamp.png" alt="" loading="lazy"></span></td>
<td>Redstone Lamp</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="redstone torch" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/redstonetorch.png" alt="" loading="lazy"></span></td>
<td>Redstone Torch</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/sandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="sandstone stairs" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sandstonestairs.png" alt="" loading="lazy"></span></td>
<td>Sandstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sandstone wall" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sandstonewall.png" alt="" loading="lazy"></span></td>
<td>Sandstone Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sculk" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/sculk.png" alt="" loading="lazy"></span></td>
<td>Sculk</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="sculk catalyst" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/sculkcatalyst.png" alt="" loading="lazy"></span></td>
<td>Sculk Catalyst</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="sculk sensor" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/sculksensor.png" alt="" loading="lazy"></span></td>
<td>Sculk Sensor</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="sculk shrieker" data-category="stone variants" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/sculkshrieker.png" alt="" loading="lazy"></span></td>
<td>Sculk Shrieker</td>
<td>Stone Variants</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="sculk vein" data-category="stone variants" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/sculkvein.png" alt="" loading="lazy"></span></td>
<td>Sculk Vein</td>
<td>Stone Variants</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="small amethyst bud" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smallamethystbud.png" alt="" loading="lazy"></span></td>
<td>Small Amethyst Bud</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="smooth basalt" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothbasalt.png" alt="" loading="lazy"></span></td>
<td>Smooth Basalt</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="smooth quartz" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothquartz.png" alt="" loading="lazy"></span></td>
<td>Smooth Quartz</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="smooth quartz slab" data-category="stone variants" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothquartzslab.png" alt="" loading="lazy"></span></td>
<td>Smooth Quartz Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="smooth quartz stairs" data-category="stone variants" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothquartzstairs.png" alt="" loading="lazy"></span></td>
<td>Smooth Quartz Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="smooth red sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothredsandstone.png" alt="" loading="lazy"></span></td>
<td>Smooth Red Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="smooth red sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothredsandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Smooth Red Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="smooth red sandstone stairs" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothredsandstonestairs.png" alt="" loading="lazy"></span></td>
<td>Smooth Red Sandstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="smooth sandstone" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothsandstone.png" alt="" loading="lazy"></span></td>
<td>Smooth Sandstone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="smooth sandstone slab" data-category="stone variants" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothsandstoneslab.png" alt="" loading="lazy"></span></td>
<td>Smooth Sandstone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="smooth sandstone stairs" data-category="stone variants" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothsandstonestairs.png" alt="" loading="lazy"></span></td>
<td>Smooth Sandstone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="smooth stone" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothstone.png" alt="" loading="lazy"></span></td>
<td>Smooth Stone</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="smooth stone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/smoothstoneslab.png" alt="" loading="lazy"></span></td>
<td>Smooth Stone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="snow" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/snow.png" alt="" loading="lazy"></span></td>
<td>Snow</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="stone brick slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/stonebrickslab.png" alt="" loading="lazy"></span></td>
<td>Stone Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="stone brick stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonebrickstairs.png" alt="" loading="lazy"></span></td>
<td>Stone Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stone brick wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonebrickwall.png" alt="" loading="lazy"></span></td>
<td>Stone Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stone bricks" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonebricks.png" alt="" loading="lazy"></span></td>
<td>Stone Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stone button" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonebutton.png" alt="" loading="lazy"></span></td>
<td>Stone Button</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stone pressure plate" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonepressureplate.png" alt="" loading="lazy"></span></td>
<td>Stone Pressure Plate</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stone slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/stoneslab.png" alt="" loading="lazy"></span></td>
<td>Stone Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="stone stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonestairs.png" alt="" loading="lazy"></span></td>
<td>Stone Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="stonecutter" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/stonecutter.png" alt="" loading="lazy"></span></td>
<td>Stonecutter</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="sulfur brick slab" data-category="stone variants" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurbrickslab.png" alt="" loading="lazy"></span></td>
<td>Sulfur Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="sulfur brick stairs" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Sulfur Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="tuff brick slab" data-category="stone variants" data-price="0.6">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffbrickslab.png" alt="" loading="lazy"></span></td>
<td>Tuff Brick Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.60</td>
</tr>
<tr data-name="tuff brick stairs" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffbrickstairs.png" alt="" loading="lazy"></span></td>
<td>Tuff Brick Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="tuff brick wall" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffbrickwall.png" alt="" loading="lazy"></span></td>
<td>Tuff Brick Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="tuff bricks" data-category="stone variants" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffbricks.png" alt="" loading="lazy"></span></td>
<td>Tuff Bricks</td>
<td>Stone Variants</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="tuff slab" data-category="stone variants" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffslab.png" alt="" loading="lazy"></span></td>
<td>Tuff Slab</td>
<td>Stone Variants</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="tuff stairs" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffstairs.png" alt="" loading="lazy"></span></td>
<td>Tuff Stairs</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="tuff wall" data-category="stone variants" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/tuffwall.png" alt="" loading="lazy"></span></td>
<td>Tuff Wall</td>
<td>Stone Variants</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="allium" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/allium.png" alt="" loading="lazy"></span></td>
<td>Allium</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="azalea" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/azalea.png" alt="" loading="lazy"></span></td>
<td>Azalea</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="azalea leaves" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/azalealeaves.png" alt="" loading="lazy"></span></td>
<td>Azalea Leaves</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="azure bluet" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/azurebluet.png" alt="" loading="lazy"></span></td>
<td>Azure Bluet</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="big dripleaf" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bigdripleaf.png" alt="" loading="lazy"></span></td>
<td>Big Dripleaf</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="blue orchid" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/blueorchid.png" alt="" loading="lazy"></span></td>
<td>Blue Orchid</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="brown mushroom block" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/brownmushroomblock.png" alt="" loading="lazy"></span></td>
<td>Brown Mushroom Block</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="bush" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/bush.png" alt="" loading="lazy"></span></td>
<td>Bush</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="cactus flower" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cactusflower.png" alt="" loading="lazy"></span></td>
<td>Cactus Flower</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="chorus flower" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/chorusflower.png" alt="" loading="lazy"></span></td>
<td>Chorus Flower</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="chorus plant" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/chorusplant.png" alt="" loading="lazy"></span></td>
<td>Chorus Plant</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="closed eyeblossom" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/closedeyeblossom.png" alt="" loading="lazy"></span></td>
<td>Closed Eyeblossom</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cornflower" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cornflower.png" alt="" loading="lazy"></span></td>
<td>Cornflower</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="crimson nylium" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonnylium.png" alt="" loading="lazy"></span></td>
<td>Crimson Nylium</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="crimson roots" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/crimsonroots.png" alt="" loading="lazy"></span></td>
<td>Crimson Roots</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="dandelion" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/dandelion.png" alt="" loading="lazy"></span></td>
<td>Dandelion</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="dead bush" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbush.png" alt="" loading="lazy"></span></td>
<td>Dead Bush</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="fern" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/fern.png" alt="" loading="lazy"></span></td>
<td>Fern</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="firefly bush" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/fireflybush.png" alt="" loading="lazy"></span></td>
<td>Firefly Bush</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="flowering azalea" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/floweringazalea.png" alt="" loading="lazy"></span></td>
<td>Flowering Azalea</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="flowering azalea leaves" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/floweringazalealeaves.png" alt="" loading="lazy"></span></td>
<td>Flowering Azalea Leaves</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="glow lichen" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/glowlichen.png" alt="" loading="lazy"></span></td>
<td>Glow Lichen</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="golden dandelion" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/goldendandelion.png" alt="" loading="lazy"></span></td>
<td>Golden Dandelion</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="hanging roots" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/hangingroots.png" alt="" loading="lazy"></span></td>
<td>Hanging Roots</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="large fern" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/largefern.png" alt="" loading="lazy"></span></td>
<td>Large Fern</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="leaf litter" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/leaflitter.png" alt="" loading="lazy"></span></td>
<td>Leaf Litter</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="lilac" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lilac.png" alt="" loading="lazy"></span></td>
<td>Lilac</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="lily of the valley" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lilyofthevalley.png" alt="" loading="lazy"></span></td>
<td>Lily of the Valley</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="lily pad" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/lilypad.png" alt="" loading="lazy"></span></td>
<td>Lily Pad</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mangrove roots" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mangroveroots.png" alt="" loading="lazy"></span></td>
<td>Mangrove Roots</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="moss block" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mossblock.png" alt="" loading="lazy"></span></td>
<td>Moss Block</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="moss carpet" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/mosscarpet.png" alt="" loading="lazy"></span></td>
<td>Moss Carpet</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="muddy mangrove roots" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/muddymangroveroots.png" alt="" loading="lazy"></span></td>
<td>Muddy Mangrove Roots</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="mushroom stem" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/mushroomstem.png" alt="" loading="lazy"></span></td>
<td>Mushroom Stem</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="nether sprouts" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/nethersprouts.png" alt="" loading="lazy"></span></td>
<td>Nether Sprouts</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="ochre froglight" data-category="plants &amp; natural blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/ochrefroglight.png" alt="" loading="lazy"></span></td>
<td>Ochre Froglight</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="open eyeblossom" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/openeyeblossom.png" alt="" loading="lazy"></span></td>
<td>Open Eyeblossom</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="orange tulip" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/orangetulip.png" alt="" loading="lazy"></span></td>
<td>Orange Tulip</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="oxeye daisy" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/oxeyedaisy.png" alt="" loading="lazy"></span></td>
<td>Oxeye Daisy</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pale hanging moss" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/palehangingmoss.png" alt="" loading="lazy"></span></td>
<td>Pale Hanging Moss</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pale moss block" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/palemossblock.png" alt="" loading="lazy"></span></td>
<td>Pale Moss Block</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pale moss carpet" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/palemosscarpet.png" alt="" loading="lazy"></span></td>
<td>Pale Moss Carpet</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pearlescent froglight" data-category="plants &amp; natural blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/pearlescentfroglight.png" alt="" loading="lazy"></span></td>
<td>Pearlescent Froglight</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="peony" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/peony.png" alt="" loading="lazy"></span></td>
<td>Peony</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pink petals" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkpetals.png" alt="" loading="lazy"></span></td>
<td>Pink Petals</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pink tulip" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/pinktulip.png" alt="" loading="lazy"></span></td>
<td>Pink Tulip</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pitcher plant" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/pitcherplant.png" alt="" loading="lazy"></span></td>
<td>Pitcher Plant</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pitcher pod" data-category="plants &amp; natural blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/pitcherpod.png" alt="" loading="lazy"></span></td>
<td>Pitcher Pod</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="poppy" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/poppy.png" alt="" loading="lazy"></span></td>
<td>Poppy</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="red mushroom block" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/redmushroomblock.png" alt="" loading="lazy"></span></td>
<td>Red Mushroom Block</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="red tulip" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/redtulip.png" alt="" loading="lazy"></span></td>
<td>Red Tulip</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="rose bush" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/rosebush.png" alt="" loading="lazy"></span></td>
<td>Rose Bush</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="seagrass" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/seagrass.png" alt="" loading="lazy"></span></td>
<td>Seagrass</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="short dry grass" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/shortdrygrass.png" alt="" loading="lazy"></span></td>
<td>Short Dry Grass</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="short grass" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/shortgrass.png" alt="" loading="lazy"></span></td>
<td>Short Grass</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="small dripleaf" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/smalldripleaf.png" alt="" loading="lazy"></span></td>
<td>Small Dripleaf</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="spore blossom" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/sporeblossom.png" alt="" loading="lazy"></span></td>
<td>Spore Blossom</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="sunflower" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/sunflower.png" alt="" loading="lazy"></span></td>
<td>Sunflower</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="tall dry grass" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/talldrygrass.png" alt="" loading="lazy"></span></td>
<td>Tall Dry Grass</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="tall grass" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/tallgrass.png" alt="" loading="lazy"></span></td>
<td>Tall Grass</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="torchflower" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/torchflower.png" alt="" loading="lazy"></span></td>
<td>Torchflower</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="torchflower seeds" data-category="plants &amp; natural blocks" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/torchflowerseeds.png" alt="" loading="lazy"></span></td>
<td>Torchflower Seeds</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="twisting vines" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/twistingvines.png" alt="" loading="lazy"></span></td>
<td>Twisting Vines</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="verdant froglight" data-category="plants &amp; natural blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/verdantfroglight.png" alt="" loading="lazy"></span></td>
<td>Verdant Froglight</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="vine" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/vine.png" alt="" loading="lazy"></span></td>
<td>Vine</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped nylium" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpednylium.png" alt="" loading="lazy"></span></td>
<td>Warped Nylium</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped roots" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedroots.png" alt="" loading="lazy"></span></td>
<td>Warped Roots</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="warped wart block" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedwartblock.png" alt="" loading="lazy"></span></td>
<td>Warped Wart Block</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="weeping vines" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/weepingvines.png" alt="" loading="lazy"></span></td>
<td>Weeping Vines</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="white tulip" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/whitetulip.png" alt="" loading="lazy"></span></td>
<td>White Tulip</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="wildflowers" data-category="plants &amp; natural blocks" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/wildflowers.png" alt="" loading="lazy"></span></td>
<td>Wildflowers</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="wither rose" data-category="plants &amp; natural blocks" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/witherrose.png" alt="" loading="lazy"></span></td>
<td>Wither Rose</td>
<td>Plants &amp; Natural Blocks</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="brain coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/braincoral.png" alt="" loading="lazy"></span></td>
<td>Brain Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="brain coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/braincoralblock.png" alt="" loading="lazy"></span></td>
<td>Brain Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="brain coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/braincoralfan.png" alt="" loading="lazy"></span></td>
<td>Brain Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="bubble coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/bubblecoral.png" alt="" loading="lazy"></span></td>
<td>Bubble Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="bubble coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/bubblecoralblock.png" alt="" loading="lazy"></span></td>
<td>Bubble Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="bubble coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/bubblecoralfan.png" alt="" loading="lazy"></span></td>
<td>Bubble Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead brain coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbraincoral.png" alt="" loading="lazy"></span></td>
<td>Dead Brain Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead brain coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbraincoralblock.png" alt="" loading="lazy"></span></td>
<td>Dead Brain Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dead brain coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbraincoralfan.png" alt="" loading="lazy"></span></td>
<td>Dead Brain Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead bubble coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbubblecoral.png" alt="" loading="lazy"></span></td>
<td>Dead Bubble Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead bubble coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbubblecoralblock.png" alt="" loading="lazy"></span></td>
<td>Dead Bubble Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dead bubble coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadbubblecoralfan.png" alt="" loading="lazy"></span></td>
<td>Dead Bubble Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead fire coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadfirecoral.png" alt="" loading="lazy"></span></td>
<td>Dead Fire Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead fire coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deadfirecoralblock.png" alt="" loading="lazy"></span></td>
<td>Dead Fire Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dead fire coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadfirecoralfan.png" alt="" loading="lazy"></span></td>
<td>Dead Fire Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead horn coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadhorncoral.png" alt="" loading="lazy"></span></td>
<td>Dead Horn Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead horn coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deadhorncoralblock.png" alt="" loading="lazy"></span></td>
<td>Dead Horn Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dead horn coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadhorncoralfan.png" alt="" loading="lazy"></span></td>
<td>Dead Horn Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead tube coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadtubecoral.png" alt="" loading="lazy"></span></td>
<td>Dead Tube Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="dead tube coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/deadtubecoralblock.png" alt="" loading="lazy"></span></td>
<td>Dead Tube Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dead tube coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/deadtubecoralfan.png" alt="" loading="lazy"></span></td>
<td>Dead Tube Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="fire coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/firecoral.png" alt="" loading="lazy"></span></td>
<td>Fire Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="fire coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/firecoralblock.png" alt="" loading="lazy"></span></td>
<td>Fire Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="fire coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/firecoralfan.png" alt="" loading="lazy"></span></td>
<td>Fire Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="horn coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/horncoral.png" alt="" loading="lazy"></span></td>
<td>Horn Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="horn coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/horncoralblock.png" alt="" loading="lazy"></span></td>
<td>Horn Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="horn coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/horncoralfan.png" alt="" loading="lazy"></span></td>
<td>Horn Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="tube coral" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/tubecoral.png" alt="" loading="lazy"></span></td>
<td>Tube Coral</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="tube coral block" data-category="ocean blocks" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/tubecoralblock.png" alt="" loading="lazy"></span></td>
<td>Tube Coral Block</td>
<td>Ocean Blocks</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="tube coral fan" data-category="ocean blocks" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/tubecoralfan.png" alt="" loading="lazy"></span></td>
<td>Tube Coral Fan</td>
<td>Ocean Blocks</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="black banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/blackbanner.png" alt="" loading="lazy"></span></td>
<td>Black Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="black bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Black Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="black bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackbundle.png" alt="" loading="lazy"></span></td>
<td>Black Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="black candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackcandle.png" alt="" loading="lazy"></span></td>
<td>Black Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="black carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/blackcarpet.png" alt="" loading="lazy"></span></td>
<td>Black Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="black concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/blackconcrete.png" alt="" loading="lazy"></span></td>
<td>Black Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="black concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/blackconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Black Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="black glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blackglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Black Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="black harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/blackharness.png" alt="" loading="lazy"></span></td>
<td>Black Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="black shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/blackshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Black Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="black stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstainedglass.png" alt="" loading="lazy"></span></td>
<td>Black Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="black stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/blackstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Black Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="black terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blackterracotta.png" alt="" loading="lazy"></span></td>
<td>Black Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="blue banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/bluebanner.png" alt="" loading="lazy"></span></td>
<td>Blue Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="blue bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Blue Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="blue bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/bluebundle.png" alt="" loading="lazy"></span></td>
<td>Blue Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="blue candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/bluecandle.png" alt="" loading="lazy"></span></td>
<td>Blue Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="blue carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/bluecarpet.png" alt="" loading="lazy"></span></td>
<td>Blue Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="blue concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/blueconcrete.png" alt="" loading="lazy"></span></td>
<td>Blue Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="blue concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/blueconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Blue Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="blue glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blueglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Blue Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="blue harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/blueharness.png" alt="" loading="lazy"></span></td>
<td>Blue Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="blue shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/blueshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Blue Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="blue stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/bluestainedglass.png" alt="" loading="lazy"></span></td>
<td>Blue Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="blue stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/bluestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Blue Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="blue terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/blueterracotta.png" alt="" loading="lazy"></span></td>
<td>Blue Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="brown banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/brownbanner.png" alt="" loading="lazy"></span></td>
<td>Brown Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="brown bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Brown Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="brown bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/brownbundle.png" alt="" loading="lazy"></span></td>
<td>Brown Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="brown candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/browncandle.png" alt="" loading="lazy"></span></td>
<td>Brown Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="brown carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/browncarpet.png" alt="" loading="lazy"></span></td>
<td>Brown Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="brown concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/brownconcrete.png" alt="" loading="lazy"></span></td>
<td>Brown Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="brown concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/brownconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Brown Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="brown glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/brownglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Brown Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="brown harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/brownharness.png" alt="" loading="lazy"></span></td>
<td>Brown Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="brown shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/brownshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Brown Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="brown stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/brownstainedglass.png" alt="" loading="lazy"></span></td>
<td>Brown Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="brown stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/brownstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Brown Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="brown terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/brownterracotta.png" alt="" loading="lazy"></span></td>
<td>Brown Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/candle.png" alt="" loading="lazy"></span></td>
<td>Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cyan banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanbanner.png" alt="" loading="lazy"></span></td>
<td>Cyan Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="cyan bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Cyan Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="cyan bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanbundle.png" alt="" loading="lazy"></span></td>
<td>Cyan Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cyan candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/cyancandle.png" alt="" loading="lazy"></span></td>
<td>Cyan Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="cyan carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cyancarpet.png" alt="" loading="lazy"></span></td>
<td>Cyan Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cyan concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanconcrete.png" alt="" loading="lazy"></span></td>
<td>Cyan Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="cyan concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Cyan Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="cyan glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Cyan Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="cyan harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanharness.png" alt="" loading="lazy"></span></td>
<td>Cyan Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="cyan shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Cyan Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="cyan stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanstainedglass.png" alt="" loading="lazy"></span></td>
<td>Cyan Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="cyan stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Cyan Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="cyan terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cyanterracotta.png" alt="" loading="lazy"></span></td>
<td>Cyan Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="gray banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/graybanner.png" alt="" loading="lazy"></span></td>
<td>Gray Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="gray bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Gray Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="gray bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/graybundle.png" alt="" loading="lazy"></span></td>
<td>Gray Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="gray candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/graycandle.png" alt="" loading="lazy"></span></td>
<td>Gray Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="gray carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/graycarpet.png" alt="" loading="lazy"></span></td>
<td>Gray Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="gray concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/grayconcrete.png" alt="" loading="lazy"></span></td>
<td>Gray Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="gray concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/grayconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Gray Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="gray glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/grayglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Gray Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="gray harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/grayharness.png" alt="" loading="lazy"></span></td>
<td>Gray Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="gray shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/grayshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Gray Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="gray stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/graystainedglass.png" alt="" loading="lazy"></span></td>
<td>Gray Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="gray stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/graystainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Gray Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="gray terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/grayterracotta.png" alt="" loading="lazy"></span></td>
<td>Gray Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="green banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/greenbanner.png" alt="" loading="lazy"></span></td>
<td>Green Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="green bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Green Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="green bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/greenbundle.png" alt="" loading="lazy"></span></td>
<td>Green Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="green candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/greencandle.png" alt="" loading="lazy"></span></td>
<td>Green Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="green carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/greencarpet.png" alt="" loading="lazy"></span></td>
<td>Green Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="green concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/greenconcrete.png" alt="" loading="lazy"></span></td>
<td>Green Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="green concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/greenconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Green Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="green glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/greenglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Green Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="green harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/greenharness.png" alt="" loading="lazy"></span></td>
<td>Green Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="green shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/greenshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Green Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="green stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/greenstainedglass.png" alt="" loading="lazy"></span></td>
<td>Green Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="green stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/greenstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Green Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="green terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/greenterracotta.png" alt="" loading="lazy"></span></td>
<td>Green Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light blue banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluebanner.png" alt="" loading="lazy"></span></td>
<td>Light Blue Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="light blue bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Light Blue Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="light blue bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluebundle.png" alt="" loading="lazy"></span></td>
<td>Light Blue Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="light blue candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluecandle.png" alt="" loading="lazy"></span></td>
<td>Light Blue Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="light blue carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluecarpet.png" alt="" loading="lazy"></span></td>
<td>Light Blue Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="light blue concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueconcrete.png" alt="" loading="lazy"></span></td>
<td>Light Blue Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="light blue concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Light Blue Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="light blue glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Light Blue Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light blue harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueharness.png" alt="" loading="lazy"></span></td>
<td>Light Blue Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="light blue shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Light Blue Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="light blue stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluestainedglass.png" alt="" loading="lazy"></span></td>
<td>Light Blue Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="light blue stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightbluestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Light Blue Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="light blue terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightblueterracotta.png" alt="" loading="lazy"></span></td>
<td>Light Blue Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light gray banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraybanner.png" alt="" loading="lazy"></span></td>
<td>Light Gray Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="light gray bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Light Gray Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="light gray bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraybundle.png" alt="" loading="lazy"></span></td>
<td>Light Gray Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="light gray candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraycandle.png" alt="" loading="lazy"></span></td>
<td>Light Gray Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="light gray carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraycarpet.png" alt="" loading="lazy"></span></td>
<td>Light Gray Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="light gray concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayconcrete.png" alt="" loading="lazy"></span></td>
<td>Light Gray Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="light gray concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Light Gray Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="light gray glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Light Gray Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="light gray harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayharness.png" alt="" loading="lazy"></span></td>
<td>Light Gray Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="light gray shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Light Gray Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="light gray stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraystainedglass.png" alt="" loading="lazy"></span></td>
<td>Light Gray Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="light gray stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgraystainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Light Gray Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="light gray terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/lightgrayterracotta.png" alt="" loading="lazy"></span></td>
<td>Light Gray Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="lime banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/limebanner.png" alt="" loading="lazy"></span></td>
<td>Lime Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="lime bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Lime Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="lime bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/limebundle.png" alt="" loading="lazy"></span></td>
<td>Lime Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="lime candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/limecandle.png" alt="" loading="lazy"></span></td>
<td>Lime Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="lime carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/limecarpet.png" alt="" loading="lazy"></span></td>
<td>Lime Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="lime concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/limeconcrete.png" alt="" loading="lazy"></span></td>
<td>Lime Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="lime concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/limeconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Lime Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="lime glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/limeglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Lime Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="lime harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/limeharness.png" alt="" loading="lazy"></span></td>
<td>Lime Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="lime shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/limeshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Lime Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="lime stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/limestainedglass.png" alt="" loading="lazy"></span></td>
<td>Lime Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="lime stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/limestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Lime Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="lime terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/limeterracotta.png" alt="" loading="lazy"></span></td>
<td>Lime Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="magenta banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/magentabanner.png" alt="" loading="lazy"></span></td>
<td>Magenta Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="magenta bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Magenta Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="magenta bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/magentabundle.png" alt="" loading="lazy"></span></td>
<td>Magenta Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="magenta candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/magentacandle.png" alt="" loading="lazy"></span></td>
<td>Magenta Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="magenta carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/magentacarpet.png" alt="" loading="lazy"></span></td>
<td>Magenta Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="magenta concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/magentaconcrete.png" alt="" loading="lazy"></span></td>
<td>Magenta Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="magenta concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/magentaconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Magenta Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="magenta glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/magentaglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Magenta Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="magenta harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/magentaharness.png" alt="" loading="lazy"></span></td>
<td>Magenta Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="magenta shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/magentashulkerbox.png" alt="" loading="lazy"></span></td>
<td>Magenta Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="magenta stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/magentastainedglass.png" alt="" loading="lazy"></span></td>
<td>Magenta Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="magenta stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/magentastainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Magenta Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="magenta terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/magentaterracotta.png" alt="" loading="lazy"></span></td>
<td>Magenta Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="orange banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/orangebanner.png" alt="" loading="lazy"></span></td>
<td>Orange Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="orange bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Orange Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="orange bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/orangebundle.png" alt="" loading="lazy"></span></td>
<td>Orange Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="orange candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/orangecandle.png" alt="" loading="lazy"></span></td>
<td>Orange Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="orange carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/orangecarpet.png" alt="" loading="lazy"></span></td>
<td>Orange Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="orange concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeconcrete.png" alt="" loading="lazy"></span></td>
<td>Orange Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="orange concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Orange Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="orange glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Orange Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="orange harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeharness.png" alt="" loading="lazy"></span></td>
<td>Orange Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="orange shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Orange Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="orange stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/orangestainedglass.png" alt="" loading="lazy"></span></td>
<td>Orange Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="orange stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/orangestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Orange Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="orange terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/orangeterracotta.png" alt="" loading="lazy"></span></td>
<td>Orange Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="pink banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkbanner.png" alt="" loading="lazy"></span></td>
<td>Pink Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="pink bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Pink Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="pink bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkbundle.png" alt="" loading="lazy"></span></td>
<td>Pink Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pink candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkcandle.png" alt="" loading="lazy"></span></td>
<td>Pink Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="pink carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkcarpet.png" alt="" loading="lazy"></span></td>
<td>Pink Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pink concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkconcrete.png" alt="" loading="lazy"></span></td>
<td>Pink Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="pink concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Pink Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="pink glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Pink Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="pink harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkharness.png" alt="" loading="lazy"></span></td>
<td>Pink Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="pink shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Pink Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="pink stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkstainedglass.png" alt="" loading="lazy"></span></td>
<td>Pink Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="pink stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Pink Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="pink terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/pinkterracotta.png" alt="" loading="lazy"></span></td>
<td>Pink Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="purple banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/purplebanner.png" alt="" loading="lazy"></span></td>
<td>Purple Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="purple bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Purple Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="purple bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/purplebundle.png" alt="" loading="lazy"></span></td>
<td>Purple Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="purple candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/purplecandle.png" alt="" loading="lazy"></span></td>
<td>Purple Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="purple carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/purplecarpet.png" alt="" loading="lazy"></span></td>
<td>Purple Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="purple concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleconcrete.png" alt="" loading="lazy"></span></td>
<td>Purple Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="purple concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Purple Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="purple glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Purple Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="purple harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleharness.png" alt="" loading="lazy"></span></td>
<td>Purple Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="purple shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Purple Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="purple stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/purplestainedglass.png" alt="" loading="lazy"></span></td>
<td>Purple Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="purple stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/purplestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Purple Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="purple terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/purpleterracotta.png" alt="" loading="lazy"></span></td>
<td>Purple Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="red banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/redbanner.png" alt="" loading="lazy"></span></td>
<td>Red Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="red bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Red Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="red bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/redbundle.png" alt="" loading="lazy"></span></td>
<td>Red Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="red candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/redcandle.png" alt="" loading="lazy"></span></td>
<td>Red Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="red carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/redcarpet.png" alt="" loading="lazy"></span></td>
<td>Red Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="red concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/redconcrete.png" alt="" loading="lazy"></span></td>
<td>Red Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="red concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/redconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Red Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="red glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Red Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="red harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/redharness.png" alt="" loading="lazy"></span></td>
<td>Red Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="red shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/redshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Red Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="red stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/redstainedglass.png" alt="" loading="lazy"></span></td>
<td>Red Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="red stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/redstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Red Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="red terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/redterracotta.png" alt="" loading="lazy"></span></td>
<td>Red Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/terracotta.png" alt="" loading="lazy"></span></td>
<td>Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="tinted glass" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/tintedglass.png" alt="" loading="lazy"></span></td>
<td>Tinted Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="white banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/whitebanner.png" alt="" loading="lazy"></span></td>
<td>White Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="white bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>White Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="white bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/whitebundle.png" alt="" loading="lazy"></span></td>
<td>White Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="white candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/whitecandle.png" alt="" loading="lazy"></span></td>
<td>White Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="white carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/whitecarpet.png" alt="" loading="lazy"></span></td>
<td>White Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="white concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteconcrete.png" alt="" loading="lazy"></span></td>
<td>White Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="white concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteconcretepowder.png" alt="" loading="lazy"></span></td>
<td>White Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="white glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>White Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="white harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteharness.png" alt="" loading="lazy"></span></td>
<td>White Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="white shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteshulkerbox.png" alt="" loading="lazy"></span></td>
<td>White Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="white stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/whitestainedglass.png" alt="" loading="lazy"></span></td>
<td>White Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="white stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/whitestainedglasspane.png" alt="" loading="lazy"></span></td>
<td>White Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="white terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/whiteterracotta.png" alt="" loading="lazy"></span></td>
<td>White Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="yellow banner" data-category="colored blocks &amp; decor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowbanner.png" alt="" loading="lazy"></span></td>
<td>Yellow Banner</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="yellow bed" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Yellow Bed</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="yellow bundle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowbundle.png" alt="" loading="lazy"></span></td>
<td>Yellow Bundle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="yellow candle" data-category="colored blocks &amp; decor" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowcandle.png" alt="" loading="lazy"></span></td>
<td>Yellow Candle</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="yellow carpet" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowcarpet.png" alt="" loading="lazy"></span></td>
<td>Yellow Carpet</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="yellow concrete" data-category="colored blocks &amp; decor" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowconcrete.png" alt="" loading="lazy"></span></td>
<td>Yellow Concrete</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="yellow concrete powder" data-category="colored blocks &amp; decor" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowconcretepowder.png" alt="" loading="lazy"></span></td>
<td>Yellow Concrete Powder</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="yellow glazed terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowglazedterracotta.png" alt="" loading="lazy"></span></td>
<td>Yellow Glazed Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="yellow harness" data-category="colored blocks &amp; decor" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowharness.png" alt="" loading="lazy"></span></td>
<td>Yellow Harness</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="yellow shulker box" data-category="colored blocks &amp; decor" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowshulkerbox.png" alt="" loading="lazy"></span></td>
<td>Yellow Shulker Box</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="yellow stained glass" data-category="colored blocks &amp; decor" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowstainedglass.png" alt="" loading="lazy"></span></td>
<td>Yellow Stained Glass</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="yellow stained glass pane" data-category="colored blocks &amp; decor" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowstainedglasspane.png" alt="" loading="lazy"></span></td>
<td>Yellow Stained Glass Pane</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="yellow terracotta" data-category="colored blocks &amp; decor" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/yellowterracotta.png" alt="" loading="lazy"></span></td>
<td>Yellow Terracotta</td>
<td>Colored Blocks &amp; Decor</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="activator rail" data-category="utility items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/activatorrail.png" alt="" loading="lazy"></span></td>
<td>Activator Rail</td>
<td>Utility Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="anvil" data-category="utility items" data-price="120">
<td><span class="sp-icon"><img src="/assets/items/sell/anvil.png" alt="" loading="lazy"></span></td>
<td>Anvil</td>
<td>Utility Items</td>
<td class="sp-price">$120.00</td>
</tr>
<tr data-name="axolotl bucket" data-category="utility items" data-price="14">
<td><span class="sp-icon"><img src="/assets/items/sell/axolotlbucket.png" alt="" loading="lazy"></span></td>
<td>Axolotl Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$14.00</td>
</tr>
<tr data-name="barrel" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/barrel.png" alt="" loading="lazy"></span></td>
<td>Barrel</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="beacon" data-category="utility items" data-price="60">
<td><span class="sp-icon"><img src="/assets/items/sell/beacon.png" alt="" loading="lazy"></span></td>
<td>Beacon</td>
<td>Utility Items</td>
<td class="sp-price">$60.00</td>
</tr>
<tr data-name="bee nest" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/beenest.png" alt="" loading="lazy"></span></td>
<td>Bee Nest</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="beehive" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/beehive.png" alt="" loading="lazy"></span></td>
<td>Beehive</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="bell" data-category="utility items" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/bell.png" alt="" loading="lazy"></span></td>
<td>Bell</td>
<td>Utility Items</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="blast furnace" data-category="utility items" data-price="18">
<td><span class="sp-icon"><img src="/assets/items/sell/blastfurnace.png" alt="" loading="lazy"></span></td>
<td>Blast Furnace</td>
<td>Utility Items</td>
<td class="sp-price">$18.00</td>
</tr>
<tr data-name="book" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/book.png" alt="" loading="lazy"></span></td>
<td>Book</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="bookshelf" data-category="utility items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/bookshelf.png" alt="" loading="lazy"></span></td>
<td>Bookshelf</td>
<td>Utility Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="bowl" data-category="utility items" data-price="0.05">
<td><span class="sp-icon"><img src="/assets/items/sell/bowl.png" alt="" loading="lazy"></span></td>
<td>Bowl</td>
<td>Utility Items</td>
<td class="sp-price">$0.05</td>
</tr>
<tr data-name="brewing stand" data-category="utility items" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/brewingstand.png" alt="" loading="lazy"></span></td>
<td>Brewing Stand</td>
<td>Utility Items</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="bucket" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/bucket.png" alt="" loading="lazy"></span></td>
<td>Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="bundle" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/bundle.png" alt="" loading="lazy"></span></td>
<td>Bundle</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="campfire" data-category="utility items" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/campfire.png" alt="" loading="lazy"></span></td>
<td>Campfire</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="cartography table" data-category="utility items" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/cartographytable.png" alt="" loading="lazy"></span></td>
<td>Cartography Table</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="cauldron" data-category="utility items" data-price="35">
<td><span class="sp-icon"><img src="/assets/items/sell/cauldron.png" alt="" loading="lazy"></span></td>
<td>Cauldron</td>
<td>Utility Items</td>
<td class="sp-price">$35.00</td>
</tr>
<tr data-name="chest" data-category="utility items" data-price="1.2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Chest</td>
<td>Utility Items</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="chest minecart" data-category="utility items" data-price="26">
<td><span class="sp-icon"><img src="/assets/items/sell/chestminecart.png" alt="" loading="lazy"></span></td>
<td>Chest Minecart</td>
<td>Utility Items</td>
<td class="sp-price">$26.00</td>
</tr>
<tr data-name="chipped anvil" data-category="utility items" data-price="80">
<td><span class="sp-icon"><img src="/assets/items/sell/chippedanvil.png" alt="" loading="lazy"></span></td>
<td>Chipped Anvil</td>
<td>Utility Items</td>
<td class="sp-price">$80.00</td>
</tr>
<tr data-name="chiseled bookshelf" data-category="utility items" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chiseledbookshelf.png" alt="" loading="lazy"></span></td>
<td>Chiseled Bookshelf</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="clock" data-category="utility items" data-price="25">
<td><span class="sp-icon"><img src="/assets/items/sell/clock.png" alt="" loading="lazy"></span></td>
<td>Clock</td>
<td>Utility Items</td>
<td class="sp-price">$25.00</td>
</tr>
<tr data-name="cod bucket" data-category="utility items" data-price="12.5">
<td><span class="sp-icon"><img src="/assets/items/sell/codbucket.png" alt="" loading="lazy"></span></td>
<td>Cod Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.50</td>
</tr>
<tr data-name="comparator" data-category="utility items" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/comparator.png" alt="" loading="lazy"></span></td>
<td>Comparator</td>
<td>Utility Items</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="compass" data-category="utility items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/compass.png" alt="" loading="lazy"></span></td>
<td>Compass</td>
<td>Utility Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="composter" data-category="utility items" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/composter.png" alt="" loading="lazy"></span></td>
<td>Composter</td>
<td>Utility Items</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="conduit" data-category="utility items" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/conduit.png" alt="" loading="lazy"></span></td>
<td>Conduit</td>
<td>Utility Items</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="crafter" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/crafter.png" alt="" loading="lazy"></span></td>
<td>Crafter</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="crafting table" data-category="utility items" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/craftingtable.png" alt="" loading="lazy"></span></td>
<td>Crafting Table</td>
<td>Utility Items</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="damaged anvil" data-category="utility items" data-price="40">
<td><span class="sp-icon"><img src="/assets/items/sell/damagedanvil.png" alt="" loading="lazy"></span></td>
<td>Damaged Anvil</td>
<td>Utility Items</td>
<td class="sp-price">$40.00</td>
</tr>
<tr data-name="daylight detector" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/daylightdetector.png" alt="" loading="lazy"></span></td>
<td>Daylight Detector</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="detector rail" data-category="utility items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/detectorrail.png" alt="" loading="lazy"></span></td>
<td>Detector Rail</td>
<td>Utility Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="dispenser" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/dispenser.png" alt="" loading="lazy"></span></td>
<td>Dispenser</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="dropper" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/dropper.png" alt="" loading="lazy"></span></td>
<td>Dropper</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="enchanting table" data-category="utility items" data-price="100">
<td><span class="sp-icon"><img src="/assets/items/sell/enchantingtable.png" alt="" loading="lazy"></span></td>
<td>Enchanting Table</td>
<td>Utility Items</td>
<td class="sp-price">$100.00</td>
</tr>
<tr data-name="end crystal" data-category="utility items" data-price="16">
<td><span class="sp-icon"><img src="/assets/items/sell/endcrystal.png" alt="" loading="lazy"></span></td>
<td>End Crystal</td>
<td>Utility Items</td>
<td class="sp-price">$16.00</td>
</tr>
<tr data-name="ender chest" data-category="utility items" data-price="30">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Ender Chest</td>
<td>Utility Items</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="fletching table" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/fletchingtable.png" alt="" loading="lazy"></span></td>
<td>Fletching Table</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="furnace" data-category="utility items" data-price="0.4">
<td><span class="sp-icon"><img src="/assets/items/sell/furnace.png" alt="" loading="lazy"></span></td>
<td>Furnace</td>
<td>Utility Items</td>
<td class="sp-price">$0.40</td>
</tr>
<tr data-name="furnace minecart" data-category="utility items" data-price="25">
<td><span class="sp-icon"><img src="/assets/items/sell/furnaceminecart.png" alt="" loading="lazy"></span></td>
<td>Furnace Minecart</td>
<td>Utility Items</td>
<td class="sp-price">$25.00</td>
</tr>
<tr data-name="glass bottle" data-category="utility items" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/glassbottle.png" alt="" loading="lazy"></span></td>
<td>Glass Bottle</td>
<td>Utility Items</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="heavy weighted pressure plate" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/heavyweightedpressureplate.png" alt="" loading="lazy"></span></td>
<td>Heavy Weighted Pressure Plate</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="hopper" data-category="utility items" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/hopper.png" alt="" loading="lazy"></span></td>
<td>Hopper</td>
<td>Utility Items</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="hopper minecart" data-category="utility items" data-price="45">
<td><span class="sp-icon"><img src="/assets/items/sell/hopperminecart.png" alt="" loading="lazy"></span></td>
<td>Hopper Minecart</td>
<td>Utility Items</td>
<td class="sp-price">$45.00</td>
</tr>
<tr data-name="iron bars" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironbars.png" alt="" loading="lazy"></span></td>
<td>Iron Bars</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="iron chain" data-category="utility items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/ironchain.png" alt="" loading="lazy"></span></td>
<td>Iron Chain</td>
<td>Utility Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="iron door" data-category="utility items" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/irondoor.png" alt="" loading="lazy"></span></td>
<td>Iron Door</td>
<td>Utility Items</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="iron trapdoor" data-category="utility items" data-price="18">
<td><span class="sp-icon"><img src="/assets/items/sell/irontrapdoor.png" alt="" loading="lazy"></span></td>
<td>Iron Trapdoor</td>
<td>Utility Items</td>
<td class="sp-price">$18.00</td>
</tr>
<tr data-name="jack o lantern" data-category="utility items" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/jackolantern.png" alt="" loading="lazy"></span></td>
<td>Jack o Lantern</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="jukebox" data-category="utility items" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/jukebox.png" alt="" loading="lazy"></span></td>
<td>Jukebox</td>
<td>Utility Items</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="ladder" data-category="utility items" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ladder.png" alt="" loading="lazy"></span></td>
<td>Ladder</td>
<td>Utility Items</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="lantern" data-category="utility items" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/lantern.png" alt="" loading="lazy"></span></td>
<td>Lantern</td>
<td>Utility Items</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="lava bucket" data-category="utility items" data-price="13">
<td><span class="sp-icon"><img src="/assets/items/sell/lavabucket.png" alt="" loading="lazy"></span></td>
<td>Lava Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$13.00</td>
</tr>
<tr data-name="lead" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/lead.png" alt="" loading="lazy"></span></td>
<td>Lead</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="lectern" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/lectern.png" alt="" loading="lazy"></span></td>
<td>Lectern</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="lever" data-category="utility items" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/lever.png" alt="" loading="lazy"></span></td>
<td>Lever</td>
<td>Utility Items</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="light weighted pressure plate" data-category="utility items" data-price="18">
<td><span class="sp-icon"><img src="/assets/items/sell/lightweightedpressureplate.png" alt="" loading="lazy"></span></td>
<td>Light Weighted Pressure Plate</td>
<td>Utility Items</td>
<td class="sp-price">$18.00</td>
</tr>
<tr data-name="lodestone" data-category="utility items" data-price="80">
<td><span class="sp-icon"><img src="/assets/items/sell/lodestone.png" alt="" loading="lazy"></span></td>
<td>Lodestone</td>
<td>Utility Items</td>
<td class="sp-price">$80.00</td>
</tr>
<tr data-name="loom" data-category="utility items" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/loom.png" alt="" loading="lazy"></span></td>
<td>Loom</td>
<td>Utility Items</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="map" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/map.png" alt="" loading="lazy"></span></td>
<td>Map</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="milk bucket" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/milkbucket.png" alt="" loading="lazy"></span></td>
<td>Milk Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="minecart" data-category="utility items" data-price="25">
<td><span class="sp-icon"><img src="/assets/items/sell/minecart.png" alt="" loading="lazy"></span></td>
<td>Minecart</td>
<td>Utility Items</td>
<td class="sp-price">$25.00</td>
</tr>
<tr data-name="note block" data-category="utility items" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/noteblock.png" alt="" loading="lazy"></span></td>
<td>Note Block</td>
<td>Utility Items</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="observer" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/observer.png" alt="" loading="lazy"></span></td>
<td>Observer</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="piston" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/piston.png" alt="" loading="lazy"></span></td>
<td>Piston</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="powder snow bucket" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/powdersnowbucket.png" alt="" loading="lazy"></span></td>
<td>Powder Snow Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="powered rail" data-category="utility items" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/poweredrail.png" alt="" loading="lazy"></span></td>
<td>Powered Rail</td>
<td>Utility Items</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="pufferfish bucket" data-category="utility items" data-price="13">
<td><span class="sp-icon"><img src="/assets/items/sell/pufferfishbucket.png" alt="" loading="lazy"></span></td>
<td>Pufferfish Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$13.00</td>
</tr>
<tr data-name="rail" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/rail.png" alt="" loading="lazy"></span></td>
<td>Rail</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="recovery compass" data-category="utility items" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/recoverycompass.png" alt="" loading="lazy"></span></td>
<td>Recovery Compass</td>
<td>Utility Items</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="repeater" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/repeater.png" alt="" loading="lazy"></span></td>
<td>Repeater</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="respawn anchor" data-category="utility items" data-price="25">
<td><span class="sp-icon"><img src="/assets/items/sell/respawnanchor.png" alt="" loading="lazy"></span></td>
<td>Respawn Anchor</td>
<td>Utility Items</td>
<td class="sp-price">$25.00</td>
</tr>
<tr data-name="salmon bucket" data-category="utility items" data-price="12.5">
<td><span class="sp-icon"><img src="/assets/items/sell/salmonbucket.png" alt="" loading="lazy"></span></td>
<td>Salmon Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.50</td>
</tr>
<tr data-name="scaffolding" data-category="utility items" data-price="0.1">
<td><span class="sp-icon"><img src="/assets/items/sell/scaffolding.png" alt="" loading="lazy"></span></td>
<td>Scaffolding</td>
<td>Utility Items</td>
<td class="sp-price">$0.10</td>
</tr>
<tr data-name="shulker box" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/shulkerbox.png" alt="" loading="lazy"></span></td>
<td>Shulker Box</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="smithing table" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/smithingtable.png" alt="" loading="lazy"></span></td>
<td>Smithing Table</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="smoker" data-category="utility items" data-price="1.5">
<td><span class="sp-icon"><img src="/assets/items/sell/smoker.png" alt="" loading="lazy"></span></td>
<td>Smoker</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="soul campfire" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/soulcampfire.png" alt="" loading="lazy"></span></td>
<td>Soul Campfire</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="soul lantern" data-category="utility items" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/soullantern.png" alt="" loading="lazy"></span></td>
<td>Soul Lantern</td>
<td>Utility Items</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="soul torch" data-category="utility items" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/soultorch.png" alt="" loading="lazy"></span></td>
<td>Soul Torch</td>
<td>Utility Items</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="spyglass" data-category="utility items" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/spyglass.png" alt="" loading="lazy"></span></td>
<td>Spyglass</td>
<td>Utility Items</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="sticky piston" data-category="utility items" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/stickypiston.png" alt="" loading="lazy"></span></td>
<td>Sticky Piston</td>
<td>Utility Items</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="sulfur cube bucket" data-category="utility items" data-price="13">
<td><span class="sp-icon"><img src="/assets/items/sell/sulfurcubebucket.png" alt="" loading="lazy"></span></td>
<td>Sulfur Cube Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$13.00</td>
</tr>
<tr data-name="tadpole bucket" data-category="utility items" data-price="13">
<td><span class="sp-icon"><img src="/assets/items/sell/tadpolebucket.png" alt="" loading="lazy"></span></td>
<td>Tadpole Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$13.00</td>
</tr>
<tr data-name="target" data-category="utility items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/target.png" alt="" loading="lazy"></span></td>
<td>Target</td>
<td>Utility Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="tnt minecart" data-category="utility items" data-price="35">
<td><span class="sp-icon"><img src="/assets/items/sell/tntminecart.png" alt="" loading="lazy"></span></td>
<td>Tnt Minecart</td>
<td>Utility Items</td>
<td class="sp-price">$35.00</td>
</tr>
<tr data-name="torch" data-category="utility items" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/torch.png" alt="" loading="lazy"></span></td>
<td>Torch</td>
<td>Utility Items</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="trapped chest" data-category="utility items" data-price="1.5">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Trapped Chest</td>
<td>Utility Items</td>
<td class="sp-price">$1.50</td>
</tr>
<tr data-name="tripwire hook" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/tripwirehook.png" alt="" loading="lazy"></span></td>
<td>Tripwire Hook</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="tropical fish bucket" data-category="utility items" data-price="13">
<td><span class="sp-icon"><img src="/assets/items/sell/tropicalfishbucket.png" alt="" loading="lazy"></span></td>
<td>Tropical Fish Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$13.00</td>
</tr>
<tr data-name="water bucket" data-category="utility items" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/waterbucket.png" alt="" loading="lazy"></span></td>
<td>Water Bucket</td>
<td>Utility Items</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="writable book" data-category="utility items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/writablebook.png" alt="" loading="lazy"></span></td>
<td>Writable Book</td>
<td>Utility Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="armor stand" data-category="decoration" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/armorstand.png" alt="" loading="lazy"></span></td>
<td>Armor Stand</td>
<td>Decoration</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="flower pot" data-category="decoration" data-price="0.9">
<td><span class="sp-icon"><img src="/assets/items/sell/flowerpot.png" alt="" loading="lazy"></span></td>
<td>Flower Pot</td>
<td>Decoration</td>
<td class="sp-price">$0.90</td>
</tr>
<tr data-name="glow item frame" data-category="decoration" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/glowitemframe.png" alt="" loading="lazy"></span></td>
<td>Glow Item Frame</td>
<td>Decoration</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="item frame" data-category="decoration" data-price="1.2">
<td><span class="sp-icon"><img src="/assets/items/sell/itemframe.png" alt="" loading="lazy"></span></td>
<td>Item Frame</td>
<td>Decoration</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="painting" data-category="decoration" data-price="0.8">
<td><span class="sp-icon"><img src="/assets/items/sell/painting.png" alt="" loading="lazy"></span></td>
<td>Painting</td>
<td>Decoration</td>
<td class="sp-price">$0.80</td>
</tr>
<tr data-name="angler pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/anglerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Angler Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="archer pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/archerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Archer Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="arms up pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/armsuppotterysherd.png" alt="" loading="lazy"></span></td>
<td>Arms Up Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="blade pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/bladepotterysherd.png" alt="" loading="lazy"></span></td>
<td>Blade Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="brewer pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/brewerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Brewer Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="burn pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/burnpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Burn Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="danger pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/dangerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Danger Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="decorated pot" data-category="pottery sherds" data-price="1.2">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Decorated Pot</td>
<td>Pottery Sherds</td>
<td class="sp-price">$1.20</td>
</tr>
<tr data-name="explorer pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/explorerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Explorer Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="flow pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/flowpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Flow Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="friend pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/friendpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Friend Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="guster pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/gusterpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Guster Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="heart pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/heartpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Heart Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="heartbreak pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/heartbreakpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Heartbreak Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="howl pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/howlpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Howl Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="miner pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/minerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Miner Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="mourner pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/mournerpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Mourner Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="plenty pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/plentypotterysherd.png" alt="" loading="lazy"></span></td>
<td>Plenty Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="prize pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/prizepotterysherd.png" alt="" loading="lazy"></span></td>
<td>Prize Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="scrape pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/scrapepotterysherd.png" alt="" loading="lazy"></span></td>
<td>Scrape Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="sheaf pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/sheafpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Sheaf Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="shelter pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/shelterpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Shelter Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="skull pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/skullpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Skull Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="snort pottery sherd" data-category="pottery sherds" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/snortpotterysherd.png" alt="" loading="lazy"></span></td>
<td>Snort Pottery Sherd</td>
<td>Pottery Sherds</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="bolt armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/boltarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Bolt Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="coast armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/coastarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Coast Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="dune armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/dunearmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Dune Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="eye armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/eyearmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Eye Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="flow armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/flowarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Flow Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="host armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/hostarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Host Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="netherite upgrade smithing template" data-category="smithing templates" data-price="35">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteupgradesmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Netherite Upgrade Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$35.00</td>
</tr>
<tr data-name="raiser armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/raiserarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Raiser Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="rib armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/ribarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Rib Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="sentry armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/sentryarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Sentry Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="shaper armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/shaperarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Shaper Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="silence armor trim smithing template" data-category="smithing templates" data-price="40">
<td><span class="sp-icon"><img src="/assets/items/sell/silencearmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Silence Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$40.00</td>
</tr>
<tr data-name="snout armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/snoutarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Snout Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="spire armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/spirearmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Spire Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="tide armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/tidearmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Tide Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="vex armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/vexarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Vex Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="ward armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/wardarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Ward Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="wayfinder armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/wayfinderarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Wayfinder Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="wild armor trim smithing template" data-category="smithing templates" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/wildarmortrimsmithingtemplate.png" alt="" loading="lazy"></span></td>
<td>Wild Armor Trim Smithing Template</td>
<td>Smithing Templates</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="music disc 11" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisc11.png" alt="" loading="lazy"></span></td>
<td>Music Disc 11</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc 13" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisc13.png" alt="" loading="lazy"></span></td>
<td>Music Disc 13</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc 5" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisc5.png" alt="" loading="lazy"></span></td>
<td>Music Disc 5</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc blocks" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscblocks.png" alt="" loading="lazy"></span></td>
<td>Music Disc Blocks</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc bounce" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscbounce.png" alt="" loading="lazy"></span></td>
<td>Music Disc Bounce</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc cat" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisccat.png" alt="" loading="lazy"></span></td>
<td>Music Disc Cat</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc chirp" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscchirp.png" alt="" loading="lazy"></span></td>
<td>Music Disc Chirp</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc creator" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisccreator.png" alt="" loading="lazy"></span></td>
<td>Music Disc Creator</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc creator music box" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisccreatormusicbox.png" alt="" loading="lazy"></span></td>
<td>Music Disc Creator Music Box</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc far" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscfar.png" alt="" loading="lazy"></span></td>
<td>Music Disc Far</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc lava chicken" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisclavachicken.png" alt="" loading="lazy"></span></td>
<td>Music Disc Lava Chicken</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc mall" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscmall.png" alt="" loading="lazy"></span></td>
<td>Music Disc Mall</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc mellohi" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscmellohi.png" alt="" loading="lazy"></span></td>
<td>Music Disc Mellohi</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc otherside" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscotherside.png" alt="" loading="lazy"></span></td>
<td>Music Disc Otherside</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc pigstep" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscpigstep.png" alt="" loading="lazy"></span></td>
<td>Music Disc Pigstep</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc precipice" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscprecipice.png" alt="" loading="lazy"></span></td>
<td>Music Disc Precipice</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc relic" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscrelic.png" alt="" loading="lazy"></span></td>
<td>Music Disc Relic</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc stal" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscstal.png" alt="" loading="lazy"></span></td>
<td>Music Disc Stal</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc strad" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscstrad.png" alt="" loading="lazy"></span></td>
<td>Music Disc Strad</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc tears" data-category="music discs" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdisctears.png" alt="" loading="lazy"></span></td>
<td>Music Disc Tears</td>
<td>Music Discs</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="music disc wait" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscwait.png" alt="" loading="lazy"></span></td>
<td>Music Disc Wait</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="music disc ward" data-category="music discs" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/musicdiscward.png" alt="" loading="lazy"></span></td>
<td>Music Disc Ward</td>
<td>Music Discs</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="bordure indented banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/bordureindentedbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Bordure Indented Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="creeper banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/creeperbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Creeper Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="field masoned banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/fieldmasonedbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Field Masoned Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="flow banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/flowbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Flow Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="flower banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/flowerbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Flower Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="globe banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/globebannerpattern.png" alt="" loading="lazy"></span></td>
<td>Globe Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="guster banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/gusterbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Guster Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="mojang banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/mojangbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Mojang Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="piglin banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/piglinbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Piglin Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="skull banner pattern" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/skullbannerpattern.png" alt="" loading="lazy"></span></td>
<td>Skull Banner Pattern</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="creaking heart" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/creakingheart.png" alt="" loading="lazy"></span></td>
<td>Creaking Heart</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="creeper head" data-category="banner patterns" data-price="10">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Creeper Head</td>
<td>Banner Patterns</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="disc fragment 5" data-category="banner patterns" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/discfragment5.png" alt="" loading="lazy"></span></td>
<td>Disc Fragment 5</td>
<td>Banner Patterns</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="dragon head" data-category="banner patterns" data-price="100">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Dragon Head</td>
<td>Banner Patterns</td>
<td class="sp-price">$100.00</td>
</tr>
<tr data-name="dried ghast" data-category="banner patterns" data-price="20">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Dried Ghast</td>
<td>Banner Patterns</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="echo shard" data-category="banner patterns" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/echoshard.png" alt="" loading="lazy"></span></td>
<td>Echo Shard</td>
<td>Banner Patterns</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="experience bottle" data-category="banner patterns" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/experiencebottle.png" alt="" loading="lazy"></span></td>
<td>Experience Bottle</td>
<td>Banner Patterns</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="goat horn" data-category="banner patterns" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/goathorn.png" alt="" loading="lazy"></span></td>
<td>Goat Horn</td>
<td>Banner Patterns</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="heavy core" data-category="banner patterns" data-price="100">
<td><span class="sp-icon"><img src="/assets/items/sell/heavycore.png" alt="" loading="lazy"></span></td>
<td>Heavy Core</td>
<td>Banner Patterns</td>
<td class="sp-price">$100.00</td>
</tr>
<tr data-name="ominous bottle" data-category="banner patterns" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/ominousbottle.png" alt="" loading="lazy"></span></td>
<td>Ominous Bottle</td>
<td>Banner Patterns</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="ominous trial key" data-category="banner patterns" data-price="24">
<td><span class="sp-icon"><img src="/assets/items/sell/ominoustrialkey.png" alt="" loading="lazy"></span></td>
<td>Ominous Trial Key</td>
<td>Banner Patterns</td>
<td class="sp-price">$24.00</td>
</tr>
<tr data-name="piglin head" data-category="banner patterns" data-price="10">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Piglin Head</td>
<td>Banner Patterns</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="skeleton skull" data-category="banner patterns" data-price="10">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Skeleton Skull</td>
<td>Banner Patterns</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="sniffer egg" data-category="banner patterns" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/snifferegg.png" alt="" loading="lazy"></span></td>
<td>Sniffer Egg</td>
<td>Banner Patterns</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="trial key" data-category="banner patterns" data-price="16">
<td><span class="sp-icon"><img src="/assets/items/sell/trialkey.png" alt="" loading="lazy"></span></td>
<td>Trial Key</td>
<td>Banner Patterns</td>
<td class="sp-price">$16.00</td>
</tr>
<tr data-name="zombie head" data-category="banner patterns" data-price="10">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Zombie Head</td>
<td>Banner Patterns</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="wooden axe" data-category="wooden" data-price="0.7">
<td><span class="sp-icon"><img src="/assets/items/sell/woodenaxe.png" alt="" loading="lazy"></span></td>
<td>Wooden Axe</td>
<td>Wooden</td>
<td class="sp-price">$0.70</td>
</tr>
<tr data-name="wooden hoe" data-category="wooden" data-price="0.5">
<td><span class="sp-icon"><img src="/assets/items/sell/woodenhoe.png" alt="" loading="lazy"></span></td>
<td>Wooden Hoe</td>
<td>Wooden</td>
<td class="sp-price">$0.50</td>
</tr>
<tr data-name="wooden pickaxe" data-category="wooden" data-price="0.7">
<td><span class="sp-icon"><img src="/assets/items/sell/woodenpickaxe.png" alt="" loading="lazy"></span></td>
<td>Wooden Pickaxe</td>
<td>Wooden</td>
<td class="sp-price">$0.70</td>
</tr>
<tr data-name="wooden shovel" data-category="wooden" data-price="0.3">
<td><span class="sp-icon"><img src="/assets/items/sell/woodenshovel.png" alt="" loading="lazy"></span></td>
<td>Wooden Shovel</td>
<td>Wooden</td>
<td class="sp-price">$0.30</td>
</tr>
<tr data-name="wooden spear" data-category="wooden" data-price="0.7">
<td><span class="sp-icon"><img src="/assets/items/sell/woodenspear.png" alt="" loading="lazy"></span></td>
<td>Wooden Spear</td>
<td>Wooden</td>
<td class="sp-price">$0.70</td>
</tr>
<tr data-name="wooden sword" data-category="wooden" data-price="0.45">
<td><span class="sp-icon"><img src="/assets/items/sell/woodensword.png" alt="" loading="lazy"></span></td>
<td>Wooden Sword</td>
<td>Wooden</td>
<td class="sp-price">$0.45</td>
</tr>
<tr data-name="stone axe" data-category="stone" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/stoneaxe.png" alt="" loading="lazy"></span></td>
<td>Stone Axe</td>
<td>Stone</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="stone hoe" data-category="stone" data-price="0.2">
<td><span class="sp-icon"><img src="/assets/items/sell/stonehoe.png" alt="" loading="lazy"></span></td>
<td>Stone Hoe</td>
<td>Stone</td>
<td class="sp-price">$0.20</td>
</tr>
<tr data-name="stone pickaxe" data-category="stone" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/stonepickaxe.png" alt="" loading="lazy"></span></td>
<td>Stone Pickaxe</td>
<td>Stone</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="stone shovel" data-category="stone" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/stoneshovel.png" alt="" loading="lazy"></span></td>
<td>Stone Shovel</td>
<td>Stone</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="stone spear" data-category="stone" data-price="0.25">
<td><span class="sp-icon"><img src="/assets/items/sell/stonespear.png" alt="" loading="lazy"></span></td>
<td>Stone Spear</td>
<td>Stone</td>
<td class="sp-price">$0.25</td>
</tr>
<tr data-name="stone sword" data-category="stone" data-price="0.15">
<td><span class="sp-icon"><img src="/assets/items/sell/stonesword.png" alt="" loading="lazy"></span></td>
<td>Stone Sword</td>
<td>Stone</td>
<td class="sp-price">$0.15</td>
</tr>
<tr data-name="iron axe" data-category="iron" data-price="18.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironaxe.png" alt="" loading="lazy"></span></td>
<td>Iron Axe</td>
<td>Iron</td>
<td class="sp-price">$18.10</td>
</tr>
<tr data-name="iron boots" data-category="iron" data-price="24">
<td><span class="sp-icon"><img src="/assets/items/sell/ironboots.png" alt="" loading="lazy"></span></td>
<td>Iron Boots</td>
<td>Iron</td>
<td class="sp-price">$24.00</td>
</tr>
<tr data-name="iron chestplate" data-category="iron" data-price="48">
<td><span class="sp-icon"><img src="/assets/items/sell/ironchestplate.png" alt="" loading="lazy"></span></td>
<td>Iron Chestplate</td>
<td>Iron</td>
<td class="sp-price">$48.00</td>
</tr>
<tr data-name="iron helmet" data-category="iron" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/ironhelmet.png" alt="" loading="lazy"></span></td>
<td>Iron Helmet</td>
<td>Iron</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="iron hoe" data-category="iron" data-price="12.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironhoe.png" alt="" loading="lazy"></span></td>
<td>Iron Hoe</td>
<td>Iron</td>
<td class="sp-price">$12.10</td>
</tr>
<tr data-name="iron horse armor" data-category="iron" data-price="15">
<td><span class="sp-icon"><img src="/assets/items/sell/ironhorsearmor.png" alt="" loading="lazy"></span></td>
<td>Iron Horse Armor</td>
<td>Iron</td>
<td class="sp-price">$15.00</td>
</tr>
<tr data-name="iron leggings" data-category="iron" data-price="42">
<td><span class="sp-icon"><img src="/assets/items/sell/ironleggings.png" alt="" loading="lazy"></span></td>
<td>Iron Leggings</td>
<td>Iron</td>
<td class="sp-price">$42.00</td>
</tr>
<tr data-name="iron nautilus armor" data-category="iron" data-price="19">
<td><span class="sp-icon"><img src="/assets/items/sell/ironnautilusarmor.png" alt="" loading="lazy"></span></td>
<td>Iron Nautilus Armor</td>
<td>Iron</td>
<td class="sp-price">$19.00</td>
</tr>
<tr data-name="iron pickaxe" data-category="iron" data-price="18.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironpickaxe.png" alt="" loading="lazy"></span></td>
<td>Iron Pickaxe</td>
<td>Iron</td>
<td class="sp-price">$18.10</td>
</tr>
<tr data-name="iron shovel" data-category="iron" data-price="6.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironshovel.png" alt="" loading="lazy"></span></td>
<td>Iron Shovel</td>
<td>Iron</td>
<td class="sp-price">$6.10</td>
</tr>
<tr data-name="iron spear" data-category="iron" data-price="18.1">
<td><span class="sp-icon"><img src="/assets/items/sell/ironspear.png" alt="" loading="lazy"></span></td>
<td>Iron Spear</td>
<td>Iron</td>
<td class="sp-price">$18.10</td>
</tr>
<tr data-name="iron sword" data-category="iron" data-price="12.05">
<td><span class="sp-icon"><img src="/assets/items/sell/ironsword.png" alt="" loading="lazy"></span></td>
<td>Iron Sword</td>
<td>Iron</td>
<td class="sp-price">$12.05</td>
</tr>
<tr data-name="golden axe" data-category="golden" data-price="27.1">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenaxe.png" alt="" loading="lazy"></span></td>
<td>Golden Axe</td>
<td>Golden</td>
<td class="sp-price">$27.10</td>
</tr>
<tr data-name="golden boots" data-category="golden" data-price="36">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenboots.png" alt="" loading="lazy"></span></td>
<td>Golden Boots</td>
<td>Golden</td>
<td class="sp-price">$36.00</td>
</tr>
<tr data-name="golden chestplate" data-category="golden" data-price="72">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenchestplate.png" alt="" loading="lazy"></span></td>
<td>Golden Chestplate</td>
<td>Golden</td>
<td class="sp-price">$72.00</td>
</tr>
<tr data-name="golden helmet" data-category="golden" data-price="45">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenhelmet.png" alt="" loading="lazy"></span></td>
<td>Golden Helmet</td>
<td>Golden</td>
<td class="sp-price">$45.00</td>
</tr>
<tr data-name="golden hoe" data-category="golden" data-price="18.1">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenhoe.png" alt="" loading="lazy"></span></td>
<td>Golden Hoe</td>
<td>Golden</td>
<td class="sp-price">$18.10</td>
</tr>
<tr data-name="golden horse armor" data-category="golden" data-price="20">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenhorsearmor.png" alt="" loading="lazy"></span></td>
<td>Golden Horse Armor</td>
<td>Golden</td>
<td class="sp-price">$20.00</td>
</tr>
<tr data-name="golden leggings" data-category="golden" data-price="63">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenleggings.png" alt="" loading="lazy"></span></td>
<td>Golden Leggings</td>
<td>Golden</td>
<td class="sp-price">$63.00</td>
</tr>
<tr data-name="golden nautilus armor" data-category="golden" data-price="24">
<td><span class="sp-icon"><img src="/assets/items/sell/goldennautilusarmor.png" alt="" loading="lazy"></span></td>
<td>Golden Nautilus Armor</td>
<td>Golden</td>
<td class="sp-price">$24.00</td>
</tr>
<tr data-name="golden pickaxe" data-category="golden" data-price="27.1">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenpickaxe.png" alt="" loading="lazy"></span></td>
<td>Golden Pickaxe</td>
<td>Golden</td>
<td class="sp-price">$27.10</td>
</tr>
<tr data-name="golden shovel" data-category="golden" data-price="9.1">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenshovel.png" alt="" loading="lazy"></span></td>
<td>Golden Shovel</td>
<td>Golden</td>
<td class="sp-price">$9.10</td>
</tr>
<tr data-name="golden spear" data-category="golden" data-price="27.1">
<td><span class="sp-icon"><img src="/assets/items/sell/goldenspear.png" alt="" loading="lazy"></span></td>
<td>Golden Spear</td>
<td>Golden</td>
<td class="sp-price">$27.10</td>
</tr>
<tr data-name="golden sword" data-category="golden" data-price="18.05">
<td><span class="sp-icon"><img src="/assets/items/sell/goldensword.png" alt="" loading="lazy"></span></td>
<td>Golden Sword</td>
<td>Golden</td>
<td class="sp-price">$18.05</td>
</tr>
<tr data-name="diamond axe" data-category="diamond" data-price="600.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondaxe.png" alt="" loading="lazy"></span></td>
<td>Diamond Axe</td>
<td>Diamond</td>
<td class="sp-price">$600.10</td>
</tr>
<tr data-name="diamond boots" data-category="diamond" data-price="800">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondboots.png" alt="" loading="lazy"></span></td>
<td>Diamond Boots</td>
<td>Diamond</td>
<td class="sp-price">$800.00</td>
</tr>
<tr data-name="diamond chestplate" data-category="diamond" data-price="1600">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondchestplate.png" alt="" loading="lazy"></span></td>
<td>Diamond Chestplate</td>
<td>Diamond</td>
<td class="sp-price">$1600.00</td>
</tr>
<tr data-name="diamond helmet" data-category="diamond" data-price="1000">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondhelmet.png" alt="" loading="lazy"></span></td>
<td>Diamond Helmet</td>
<td>Diamond</td>
<td class="sp-price">$1000.00</td>
</tr>
<tr data-name="diamond hoe" data-category="diamond" data-price="400.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondhoe.png" alt="" loading="lazy"></span></td>
<td>Diamond Hoe</td>
<td>Diamond</td>
<td class="sp-price">$400.10</td>
</tr>
<tr data-name="diamond horse armor" data-category="diamond" data-price="250">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondhorsearmor.png" alt="" loading="lazy"></span></td>
<td>Diamond Horse Armor</td>
<td>Diamond</td>
<td class="sp-price">$250.00</td>
</tr>
<tr data-name="diamond leggings" data-category="diamond" data-price="1400">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondleggings.png" alt="" loading="lazy"></span></td>
<td>Diamond Leggings</td>
<td>Diamond</td>
<td class="sp-price">$1400.00</td>
</tr>
<tr data-name="diamond nautilus armor" data-category="diamond" data-price="254">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondnautilusarmor.png" alt="" loading="lazy"></span></td>
<td>Diamond Nautilus Armor</td>
<td>Diamond</td>
<td class="sp-price">$254.00</td>
</tr>
<tr data-name="diamond pickaxe" data-category="diamond" data-price="600.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondpickaxe.png" alt="" loading="lazy"></span></td>
<td>Diamond Pickaxe</td>
<td>Diamond</td>
<td class="sp-price">$600.10</td>
</tr>
<tr data-name="diamond shovel" data-category="diamond" data-price="200.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondshovel.png" alt="" loading="lazy"></span></td>
<td>Diamond Shovel</td>
<td>Diamond</td>
<td class="sp-price">$200.10</td>
</tr>
<tr data-name="diamond spear" data-category="diamond" data-price="600.1">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondspear.png" alt="" loading="lazy"></span></td>
<td>Diamond Spear</td>
<td>Diamond</td>
<td class="sp-price">$600.10</td>
</tr>
<tr data-name="diamond sword" data-category="diamond" data-price="400.05">
<td><span class="sp-icon"><img src="/assets/items/sell/diamondsword.png" alt="" loading="lazy"></span></td>
<td>Diamond Sword</td>
<td>Diamond</td>
<td class="sp-price">$400.05</td>
</tr>
<tr data-name="netherite axe" data-category="diamond" data-price="1915.1">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteaxe.png" alt="" loading="lazy"></span></td>
<td>Netherite Axe</td>
<td>Diamond</td>
<td class="sp-price">$1915.10</td>
</tr>
<tr data-name="netherite boots" data-category="diamond" data-price="2115">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteboots.png" alt="" loading="lazy"></span></td>
<td>Netherite Boots</td>
<td>Diamond</td>
<td class="sp-price">$2115.00</td>
</tr>
<tr data-name="netherite chestplate" data-category="diamond" data-price="2915">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritechestplate.png" alt="" loading="lazy"></span></td>
<td>Netherite Chestplate</td>
<td>Diamond</td>
<td class="sp-price">$2915.00</td>
</tr>
<tr data-name="netherite helmet" data-category="diamond" data-price="2315">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritehelmet.png" alt="" loading="lazy"></span></td>
<td>Netherite Helmet</td>
<td>Diamond</td>
<td class="sp-price">$2315.00</td>
</tr>
<tr data-name="netherite hoe" data-category="diamond" data-price="1715.1">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritehoe.png" alt="" loading="lazy"></span></td>
<td>Netherite Hoe</td>
<td>Diamond</td>
<td class="sp-price">$1715.10</td>
</tr>
<tr data-name="netherite horse armor" data-category="diamond" data-price="1565">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritehorsearmor.png" alt="" loading="lazy"></span></td>
<td>Netherite Horse Armor</td>
<td>Diamond</td>
<td class="sp-price">$1565.00</td>
</tr>
<tr data-name="netherite leggings" data-category="diamond" data-price="2715">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteleggings.png" alt="" loading="lazy"></span></td>
<td>Netherite Leggings</td>
<td>Diamond</td>
<td class="sp-price">$2715.00</td>
</tr>
<tr data-name="netherite nautilus armor" data-category="diamond" data-price="1569">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritenautilusarmor.png" alt="" loading="lazy"></span></td>
<td>Netherite Nautilus Armor</td>
<td>Diamond</td>
<td class="sp-price">$1569.00</td>
</tr>
<tr data-name="netherite pickaxe" data-category="diamond" data-price="1915.1">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritepickaxe.png" alt="" loading="lazy"></span></td>
<td>Netherite Pickaxe</td>
<td>Diamond</td>
<td class="sp-price">$1915.10</td>
</tr>
<tr data-name="netherite shovel" data-category="diamond" data-price="1515.1">
<td><span class="sp-icon"><img src="/assets/items/sell/netheriteshovel.png" alt="" loading="lazy"></span></td>
<td>Netherite Shovel</td>
<td>Diamond</td>
<td class="sp-price">$1515.10</td>
</tr>
<tr data-name="netherite spear" data-category="diamond" data-price="1915.1">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritespear.png" alt="" loading="lazy"></span></td>
<td>Netherite Spear</td>
<td>Diamond</td>
<td class="sp-price">$1915.10</td>
</tr>
<tr data-name="netherite sword" data-category="diamond" data-price="1715.05">
<td><span class="sp-icon"><img src="/assets/items/sell/netheritesword.png" alt="" loading="lazy"></span></td>
<td>Netherite Sword</td>
<td>Diamond</td>
<td class="sp-price">$1715.05</td>
</tr>
<tr data-name="copper axe" data-category="copper" data-price="4.6">
<td><span class="sp-icon"><img src="/assets/items/sell/copperaxe.png" alt="" loading="lazy"></span></td>
<td>Copper Axe</td>
<td>Copper</td>
<td class="sp-price">$4.60</td>
</tr>
<tr data-name="copper boots" data-category="copper" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/copperboots.png" alt="" loading="lazy"></span></td>
<td>Copper Boots</td>
<td>Copper</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="copper chestplate" data-category="copper" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/copperchestplate.png" alt="" loading="lazy"></span></td>
<td>Copper Chestplate</td>
<td>Copper</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="copper helmet" data-category="copper" data-price="7.5">
<td><span class="sp-icon"><img src="/assets/items/sell/copperhelmet.png" alt="" loading="lazy"></span></td>
<td>Copper Helmet</td>
<td>Copper</td>
<td class="sp-price">$7.50</td>
</tr>
<tr data-name="copper hoe" data-category="copper" data-price="3.1">
<td><span class="sp-icon"><img src="/assets/items/sell/copperhoe.png" alt="" loading="lazy"></span></td>
<td>Copper Hoe</td>
<td>Copper</td>
<td class="sp-price">$3.10</td>
</tr>
<tr data-name="copper horse armor" data-category="copper" data-price="8">
<td><span class="sp-icon"><img src="/assets/items/sell/copperhorsearmor.png" alt="" loading="lazy"></span></td>
<td>Copper Horse Armor</td>
<td>Copper</td>
<td class="sp-price">$8.00</td>
</tr>
<tr data-name="copper leggings" data-category="copper" data-price="10.5">
<td><span class="sp-icon"><img src="/assets/items/sell/copperleggings.png" alt="" loading="lazy"></span></td>
<td>Copper Leggings</td>
<td>Copper</td>
<td class="sp-price">$10.50</td>
</tr>
<tr data-name="copper nautilus armor" data-category="copper" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/coppernautilusarmor.png" alt="" loading="lazy"></span></td>
<td>Copper Nautilus Armor</td>
<td>Copper</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="copper pickaxe" data-category="copper" data-price="4.6">
<td><span class="sp-icon"><img src="/assets/items/sell/copperpickaxe.png" alt="" loading="lazy"></span></td>
<td>Copper Pickaxe</td>
<td>Copper</td>
<td class="sp-price">$4.60</td>
</tr>
<tr data-name="copper shovel" data-category="copper" data-price="1.6">
<td><span class="sp-icon"><img src="/assets/items/sell/coppershovel.png" alt="" loading="lazy"></span></td>
<td>Copper Shovel</td>
<td>Copper</td>
<td class="sp-price">$1.60</td>
</tr>
<tr data-name="copper sword" data-category="copper" data-price="3.05">
<td><span class="sp-icon"><img src="/assets/items/sell/coppersword.png" alt="" loading="lazy"></span></td>
<td>Copper Sword</td>
<td>Copper</td>
<td class="sp-price">$3.05</td>
</tr>
<tr data-name="copper spear" data-category="copper" data-price="4.6">
<td><span class="sp-icon"><img src="/assets/items/sell/copperspear.png" alt="" loading="lazy"></span></td>
<td>Copper Spear</td>
<td>Copper</td>
<td class="sp-price">$4.60</td>
</tr>
<tr data-name="chainmail boots" data-category="chainmail" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/chainmailboots.png" alt="" loading="lazy"></span></td>
<td>Chainmail Boots</td>
<td>Chainmail</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="chainmail chestplate" data-category="chainmail" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/chainmailchestplate.png" alt="" loading="lazy"></span></td>
<td>Chainmail Chestplate</td>
<td>Chainmail</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="chainmail helmet" data-category="chainmail" data-price="2.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chainmailhelmet.png" alt="" loading="lazy"></span></td>
<td>Chainmail Helmet</td>
<td>Chainmail</td>
<td class="sp-price">$2.50</td>
</tr>
<tr data-name="chainmail leggings" data-category="chainmail" data-price="3.5">
<td><span class="sp-icon"><img src="/assets/items/sell/chainmailleggings.png" alt="" loading="lazy"></span></td>
<td>Chainmail Leggings</td>
<td>Chainmail</td>
<td class="sp-price">$3.50</td>
</tr>
<tr data-name="leather boots" data-category="leather" data-price="4">
<td><span class="sp-icon"><img src="/assets/items/sell/leatherboots.png" alt="" loading="lazy"></span></td>
<td>Leather Boots</td>
<td>Leather</td>
<td class="sp-price">$4.00</td>
</tr>
<tr data-name="leather chestplate" data-category="leather" data-price="8">
<td><span class="sp-icon"><img src="/assets/items/sell/leatherchestplate.png" alt="" loading="lazy"></span></td>
<td>Leather Chestplate</td>
<td>Leather</td>
<td class="sp-price">$8.00</td>
</tr>
<tr data-name="leather helmet" data-category="leather" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/leatherhelmet.png" alt="" loading="lazy"></span></td>
<td>Leather Helmet</td>
<td>Leather</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="leather horse armor" data-category="leather" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/leatherhorsearmor.png" alt="" loading="lazy"></span></td>
<td>Leather Horse Armor</td>
<td>Leather</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="leather leggings" data-category="leather" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/leatherleggings.png" alt="" loading="lazy"></span></td>
<td>Leather Leggings</td>
<td>Leather</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="turtle helmet" data-category="scute-based armor" data-price="10">
<td><span class="sp-icon"><img src="/assets/items/sell/turtlehelmet.png" alt="" loading="lazy"></span></td>
<td>Turtle Helmet</td>
<td>Scute-based Armor</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="wolf armor" data-category="scute-based armor" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/wolfarmor.png" alt="" loading="lazy"></span></td>
<td>Wolf Armor</td>
<td>Scute-based Armor</td>
<td class="sp-price">$3.00</td>
</tr>
<tr data-name="bow" data-category="general weapons &amp; tools" data-price="1.05">
<td><span class="sp-icon"><img src="/assets/items/sell/bow.png" alt="" loading="lazy"></span></td>
<td>Bow</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$1.05</td>
</tr>
<tr data-name="brush" data-category="general weapons &amp; tools" data-price="1.85">
<td><span class="sp-icon"><img src="/assets/items/sell/brush.png" alt="" loading="lazy"></span></td>
<td>Brush</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$1.85</td>
</tr>
<tr data-name="carrot on a stick" data-category="general weapons &amp; tools" data-price="1.05">
<td><span class="sp-icon"><img src="/assets/items/sell/carrotonastick.png" alt="" loading="lazy"></span></td>
<td>Carrot on a Stick</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$1.05</td>
</tr>
<tr data-name="crossbow" data-category="general weapons &amp; tools" data-price="9">
<td><span class="sp-icon"><img src="/assets/items/sell/crossbow.png" alt="" loading="lazy"></span></td>
<td>Crossbow</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$9.00</td>
</tr>
<tr data-name="firework rocket" data-category="general weapons &amp; tools" data-price="2.4">
<td><span class="sp-icon"><img src="/assets/items/sell/fireworkrocket.png" alt="" loading="lazy"></span></td>
<td>Firework Rocket</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$2.40</td>
</tr>
<tr data-name="firework star" data-category="general weapons &amp; tools" data-price="2.4">
<td><span class="sp-icon"><img src="/assets/items/sell/fireworkstar.png" alt="" loading="lazy"></span></td>
<td>Firework Star</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$2.40</td>
</tr>
<tr data-name="fishing rod" data-category="general weapons &amp; tools" data-price="0.75">
<td><span class="sp-icon"><img src="/assets/items/sell/fishingrod.png" alt="" loading="lazy"></span></td>
<td>Fishing Rod</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$0.75</td>
</tr>
<tr data-name="flint and steel" data-category="general weapons &amp; tools" data-price="6.2">
<td><span class="sp-icon"><img src="/assets/items/sell/flintandsteel.png" alt="" loading="lazy"></span></td>
<td>Flint and Steel</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$6.20</td>
</tr>
<tr data-name="mace" data-category="general weapons &amp; tools" data-price="103">
<td><span class="sp-icon"><img src="/assets/items/sell/mace.png" alt="" loading="lazy"></span></td>
<td>Mace</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$103.00</td>
</tr>
<tr data-name="shears" data-category="general weapons &amp; tools" data-price="12">
<td><span class="sp-icon"><img src="/assets/items/sell/shears.png" alt="" loading="lazy"></span></td>
<td>Shears</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$12.00</td>
</tr>
<tr data-name="shield" data-category="general weapons &amp; tools" data-price="7.2">
<td><span class="sp-icon"><img src="/assets/items/sell/shield.png" alt="" loading="lazy"></span></td>
<td>Shield</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$7.20</td>
</tr>
<tr data-name="trident" data-category="general weapons &amp; tools" data-price="30">
<td><span class="sp-icon"><img src="/assets/items/sell/trident.png" alt="" loading="lazy"></span></td>
<td>Trident</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$30.00</td>
</tr>
<tr data-name="warped fungus on a stick" data-category="general weapons &amp; tools" data-price="0.95">
<td><span class="sp-icon"><img src="/assets/items/sell/warpedfungusonastick.png" alt="" loading="lazy"></span></td>
<td>Warped Fungus on a Stick</td>
<td>General Weapons &amp; Tools</td>
<td class="sp-price">$0.95</td>
</tr>
<tr data-name="enchanted book" data-category="potions &amp; other nbt-variable items" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/enchantedbook.png" alt="" loading="lazy"></span></td>
<td>Enchanted Book</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="filled map" data-category="potions &amp; other nbt-variable items" data-price="2">
<td><span class="sp-icon"><img src="/assets/items/sell/filledmap.png" alt="" loading="lazy"></span></td>
<td>Filled Map</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$2.00</td>
</tr>
<tr data-name="lingering potion" data-category="potions &amp; other nbt-variable items" data-price="7">
<td><span class="sp-icon"><img src="/assets/items/sell/lingeringpotion.png" alt="" loading="lazy"></span></td>
<td>Lingering Potion</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$7.00</td>
</tr>
<tr data-name="player head" data-category="potions &amp; other nbt-variable items" data-price="10">
<td><span class="sp-icon sp-icon-empty"></span></td>
<td>Player Head</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$10.00</td>
</tr>
<tr data-name="potion" data-category="potions &amp; other nbt-variable items" data-price="5">
<td><span class="sp-icon"><img src="/assets/items/sell/potion.png" alt="" loading="lazy"></span></td>
<td>Potion</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$5.00</td>
</tr>
<tr data-name="splash potion" data-category="potions &amp; other nbt-variable items" data-price="6">
<td><span class="sp-icon"><img src="/assets/items/sell/splashpotion.png" alt="" loading="lazy"></span></td>
<td>Splash Potion</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$6.00</td>
</tr>
<tr data-name="tipped arrow" data-category="potions &amp; other nbt-variable items" data-price="1">
<td><span class="sp-icon"><img src="/assets/items/sell/tippedarrow.png" alt="" loading="lazy"></span></td>
<td>Tipped Arrow</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$1.00</td>
</tr>
<tr data-name="written book" data-category="potions &amp; other nbt-variable items" data-price="3">
<td><span class="sp-icon"><img src="/assets/items/sell/writtenbook.png" alt="" loading="lazy"></span></td>
<td>Written Book</td>
<td>Potions &amp; Other NBT-variable Items</td>
<td class="sp-price">$3.00</td>
</tr>
</tbody>
</table>
</div>
</div>

<style>
#sell-prices-app { margin: 1.5em 0; }
#sp-filter {
  width: 100%; max-width: 420px; box-sizing: border-box;
  padding: 0.5em 0.75em; font-size: 1em; margin-bottom: 0.5em;
  border: 1px solid rgba(128,128,128,0.4); border-radius: 6px;
}
#sp-count { font-size: 0.85em; opacity: 0.7; margin-bottom: 0.5em; }
.sp-table-wrap { overflow-x: auto; max-height: 75vh; overflow-y: auto; border: 1px solid rgba(128,128,128,0.25); border-radius: 6px; }
#sp-table { border-collapse: collapse; width: 100%; min-width: 480px; }
#sp-table thead th {
  position: sticky; top: 0; z-index: 1;
  background: #2d2d2d; color: #fff;
  text-align: left; padding: 0.5em 0.75em; cursor: pointer; user-select: none;
  white-space: nowrap;
}
#sp-table thead th:hover { opacity: 0.85; }
#sp-table thead th.sp-sort-asc::after { content: " \25B2"; }
#sp-table thead th.sp-sort-desc::after { content: " \25BC"; }
#sp-table tbody td { padding: 0.35em 0.75em; border-bottom: 1px solid rgba(128,128,128,0.15); vertical-align: middle; }
#sp-table tbody tr:hover { background: rgba(128,128,128,0.08); }
.sp-price { font-variant-numeric: tabular-nums; text-align: right; }
.sp-icon {
  display: inline-block; width: 24px; height: 24px; overflow: hidden;
  vertical-align: middle; image-rendering: pixelated;
}
.sp-icon img { width: 24px; height: auto; image-rendering: pixelated; display: block; }
.sp-icon-empty { background: rgba(128,128,128,0.12); border-radius: 3px; }
@media (prefers-color-scheme: light) {
  #sp-table thead th { background: #eee; color: #222; }
}
</style>

<script>
(function () {
  var root = document.currentScript.closest('#sell-prices-app') || document.getElementById('sell-prices-app');
  if (!root) return;
  var table = root.querySelector('#sp-table');
  var tbody = table.querySelector('tbody');
  var filterInput = root.querySelector('#sp-filter');
  var countEl = root.querySelector('#sp-count');
  var rows = Array.prototype.slice.call(tbody.querySelectorAll('tr'));
  var headers = Array.prototype.slice.call(table.querySelectorAll('th.sp-sort'));
  var sortState = { key: null, dir: 1 };

  function updateCount() {
    var visible = rows.filter(function (r) { return r.style.display !== 'none'; }).length;
    countEl.textContent = visible + ' / ' + rows.length + ' items';
  }

  function applyFilter() {
    var q = filterInput.value.trim().toLowerCase();
    rows.forEach(function (r) {
      var match = !q || r.dataset.name.indexOf(q) !== -1 || r.dataset.category.indexOf(q) !== -1;
      r.style.display = match ? '' : 'none';
    });
    updateCount();
  }

  function sortBy(key) {
    if (sortState.key === key) sortState.dir *= -1;
    else { sortState.key = key; sortState.dir = 1; }
    headers.forEach(function (h) { h.classList.remove('sp-sort-asc', 'sp-sort-desc'); });
    var activeHeader = headers.filter(function (h) { return h.dataset.sort === key; })[0];
    if (activeHeader) activeHeader.classList.add(sortState.dir === 1 ? 'sp-sort-asc' : 'sp-sort-desc');

    var sorted = rows.slice().sort(function (a, b) {
      var av, bv;
      if (key === 'price') { av = parseFloat(a.dataset.price); bv = parseFloat(b.dataset.price); }
      else if (key === 'category') { av = a.dataset.category; bv = b.dataset.category; }
      else { av = a.dataset.name; bv = b.dataset.name; }
      if (av < bv) return -1 * sortState.dir;
      if (av > bv) return 1 * sortState.dir;
      return 0;
    });
    sorted.forEach(function (r) { tbody.appendChild(r); });
  }

  headers.forEach(function (h) {
    if (h.dataset.sort === 'icon') return;
    h.addEventListener('click', function () { sortBy(h.dataset.sort); });
  });
  filterInput.addEventListener('input', applyFilter);
  updateCount();
})();
</script>
