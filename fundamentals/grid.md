# Grid Building

Your damage in GBF is determined by your grid of 1 mainhand + 9 other weapons. The damage calculation can be quite complex, and optimal weapon grids are often not entirely agreed upon.

Note that we don't plan on providing exact cookie-cutter grids for use. Which weapons you use will always be determined by what content you are fighting, its defense, how strong its offense is, etc. Sometimes you want more cap; sometimes you are forced to use more hp; sometimes you need extra DATA because your turn count is limited. You will always want to optimize for the particular scenario.

Instead we will tell you how many of each weapon you will need at most, and you can farm all of them and mix/match appropriately based on what you need for each bit of content.

## Modifiers

Some weapons skills stack additively and others stack multiplicatively. Each category of skill that stacks additively is considered a multiplier. The three fundamental modifiers are magna, normal, and ex (unknown). Magna builds tend to be centered around magna multipliers, and primal grids tend to be centered around normal modifiers (but not always as much, in the buncle grids).

There are also hp-dependent modifiers enmity (damage at low hp) and stamina (damage at high hp). Magna enmity, magna stamina, primal enmity, and primal stamina are all multiplicative with everything else.

Finally, crit from the same source is additive in chance but crit from different sources is additive in damage (independent procs). In practice you only use one source (and only generally in primal x primal or magna x magna, or huanglong setups) for an extra 50% unique mod.

Sentence is a multiplicative modifier to everything else, but only applies to ougis. Outside of OTKs it is mostly used only in water and dark.

## Summon Modifiers

Generally every grid uses at least a single-side magna or single-side primal. These summons boost the skills of a particular set of weapons, and weapons that have more than one boosted multiplier become especially effective because the boost is quadratic - see weapons like tiamat guns or ixabas.

On element you will often to choose to use a double sided magna or primal grid. But off element or on neutral content you will often want single sided - so you can already see why you need a diverse set of weapons to fill out either situation.

Finally, for fast OTKs of easy content youll eventually want a Huanglong x Huanglong grid, which has no boosts, and therefore means you need a balanced set of weapons.

Some people try to run funky grids like Devil x Agni. There are a number of questionable things about this - first, you are missing your shiva call, so you are already going to lose to Colossus x Shiva. Secondly, the Devil and Agni have antisynergy, because Agni is going to tend to give you your normal mod already, and Devil is providing a flat normal mod. Its basically never worth it to shoehorn yourself like this just to play primal, and better to stick to conventional Primal x Primal, Primal x Ele, Magna x Magna, or Magna x Ele. (Primal x Ele is a meme)

## Damage Calculation

The most trusted place to do damage calculation is motocal. However, even it has a few problems; it is notoriously a bit difficult to use, and it is often easy to "manipulate" motocal into showing you what you want it to show by changing conditions like buffs etc. Its best use is creating enmity/stamina graphs. Also note motocal usually calculates DPT rather than DPS so it might overrate DATA in some scenarios. It also is probably sketchy when sentence is involved.

For simple calculations, you can also use the ingame calculator as long as you are aware of how to to properly use it and what its limitations are. The primary limitation is that it cannot account for crit/sentence, or elemental buffs. This means you shouldn't use it as a reference if you are changing out any crit/sentence weapons, or use it to compare single-sided to double-sided builds. (For the latter, you can manipulate the result based on the expected ele mod you think you will have, though. The calculation it gives is at 50% elemental mod on element from inherent elemental mod)
