---
title: ATM9 FAQ
description: ATM9 Frequently Asked Questions
authors: 
---

# FAQ

**All The Mods 9** Frequently Asked Questions

---

???+ Abstract "Gameplay FAQs"
	??? Question "Why can't I use modular router and watering can?"
		By default, **Mystical Agriculture** does not allow fake players to automate watering cans. If you dislike this change, it can be changed within `config/mysticalagriculture-common.toml` > `fakePlayerWatering = true`.
	
	??? Question "Do I need to chunkload all the chunks my Chunk Destroyer is going to mine?"
		You do *not* need to load chunks you're mining. You only need to chunkload the chunk the **Chunk Destroyer** is in.

	??? Question "How do I remove enchants from a book/weapon?"
		- Drop an anvil onto **Obsidian** with the enchanted book/weapon along with **Books** for each separate enchantment (EX: You have a book with 3 different enchants, you'd need 3 books to split those enchants). 
		- Enchant the anvil with **Splitting** (Only splits books/weapons with 1 enchant) or **Obliteration** (Splits any number of enchants)
		- Use the **Enchantment Extractor** from Industrial Foregoing. Provide it with **Books** and **Power**, and it will extract each enchantment on all enchanted items/books to singular books. It can also be configured to push extracted enchantments into the **Enchantment Library** from Apotheosis.

	??? Question "What's the little 3D cube next to my crosshair?"
		It's from Quark, the default keybind to toggle it is ++k++.

	??? Question "How do I find '`insert name`' biome?"
		**Nature's Compass** is a really nice tool to find any and all biomes in the modpack. Craft it, right click with it in your hand, and you can run the search for any biome you are looking for (such as the Deep Dark).

	??? Question "How do I change `/home`, `/tpa` etc cooldown?"
		To change the behavior of `/home` or to re-enable `/back` and `/rtp`, edit `saves/worldName/serverconfig/ftb-essentials.snbt`. **The world/server has to be stopped for the changes to take effect.**
	
	??? Question "Why is flight disabled?"
		Flight is disabled in certain dimensions (**The Other**, **Blue Skies**, and **Twilight Forest**), to add more difficulty towards progression. If you dislike this change, it can be disabled in `worldName/serverconfig/noflyzone.snbt`

???+ Warning "Technical FAQs"
	??? Question "I can't complete '`name of quest`' even though I fufilled the requirements?"
		You can enable edit quests in the bottom right of the quest screen (you need OP for this) and then r-click the broken quest and force complete it OR reset it's progress if you still have the items.

	??? Question "I have my chunks force loaded, but they don't run when I'm logged off."
		1. Press ++m++ to open the map.
		2. Press ++ctrl+s++ to open the server settings (requires OP).
		3. Change `Forceloading Mode` to `always`.
		
	??? Question "What's the difference between ATM9 and ATM9: No Frills?"
		[Here is a comparison](https://www.modpackindex.com/modpacks/compare?modpacks=64056,74905)
		
	??? Question "Why isn't '`insert name`' mod in ATM9 yet?"
		ATM packs does not literally contain "All The Mods". Our main focus is having mods that's not: 1) buggy, 2) ruins performance or progression. If a mod supports Minecraft version **1.20.1**, and **Forge** (Not NeoForge), you may make a [suggestion](https://github.com/AllTheMods/ATM-9/issues/1).
	
	??? Question "I found a bug/dupe in the pack. How can I report it?"
		To report bugs, dupes or similar, head over to the [ATM9 GitHub](https://github.com/AllTheMods/ATM-9/issues) and open a new issue describing the occurrence.

	??? Question "What are the recommended Java arguments for this pack?"
		- **Client arguments**: send `?args` in the **#bot-spam** channel in our [Discord](https://discord.com/invite/allthemods).
		- **Server arguments**: send `?svargs` in the **#bot=spam** channel in our [Discord](https://discord.com/invite/allthemods).

	??? Question "Why does my game crash while launching?"
		Lack of RAM most likely. Send `?allocate` in the **#bot-spam** channel in our [Discord](https://discord.com/invite/allthemods) to learn how to allocate more RAM. If that's not the problem, head to **#atm9-techsupport** and send `?logs` to see how to upload your crash/latest log.

	??? Question "I crashed and got `Error code 1`, please help"
		`Exit code 1` is a generic error from Minecraft. It is no different than "game didn't load, no longer attempting to load. Please refer to the output error log created by your launcher" if you are unsure... please feel free to ask for further instructions on how to locate, post, and get help for your specific error so that we may further assist you in our [Discord](https://discord.com/invite/allthemods). Try running `?logs` instead.

	??? Question "I'm having issues connecting to a LAN/Essentials world"
		To fix LAN/Essential some people have removed Logprot, some Oculus, some Supplementaries. None are guaranteed, none are the actual fix. We are unable reproduce it in Dev to properly diagnose it. LAN is highly unstable in big modpacks like these.
