# Information 📖

This project is created for the **Pet System**.  
It provides pets as entities — both normal and monster types — that players can own and interact with. 🐾

---

# How It Works ⚙️

- Players receive pets as custom player heads with unique textures. This feature uses the **HeadDB** plugin (optional).  
  - If HeadDB is not installed, the system will fallback to using entity spawn eggs. 🥚
- To summon a pet, players simply **right-click** the item.  
- Pet data is stored in the **database (DB)**. Each summon creates a **unique pet ID**, and despawning deletes that record. Every spawn is fresh with a new ID. 🔄
- The maximum number of pets a player can have at once is defined in the config.  
  - Setting it to `0` disables the limit entirely.  
  - A **default limit** is always present for balance but can be extended through items or commands.

---

# Features ✨

- **Race** 🧬 → Even pets of the same entity type have individual traits and uniqueness.  
- **Skin** 🎭 → Special skins for monster types and races (including custom poses and animations like walking, running, etc.).  
- **Unique Abilities** 🪄 → Pets can have both **passive** and **active** abilities.  
- **Ability Visual Effects** 🌈 → Distinct effects for abilities (visuals, particles, or animations).  
- **Aura** 🔥 → Pets can be surrounded by visual particle effects or states (default is none, but owners can set custom auras).  
- **Runes** 💎 → Add stats or powers to pets through rune slots.  
  - Configurable rune limits are built in.  
  - Extensions can raise limits depending on whether they are soft-coded or hard-coded.  
  - Additional rune slots can also be granted via items or commands.  

- **Level System** 📈 → Pets earn experience (EXP) by fighting, assisting, or completing tasks.  
  - Higher levels improve stats (health, damage, speed, or custom attributes).  
  - Certain abilities or evolutions unlock only after reaching required levels.  
  - Config options allow scaling difficulty and EXP gain.  

- **Pet Equipment** ⚔️🛡️ → Pets can wear or hold gear for stat boosts or cosmetic flair.  
  - Equipment slots: **collars, armor, saddles, accessories** (configurable).  
  - Gear can grant buffs like speed boosts, damage resistance, or ability cooldown reduction.  
  - Cosmetic-only equipment (like wings, glowing collars, or hats) for visual customization without affecting balance.  

- **Elemental Affinity** 🌪️ → Pets can align with an element such as **Fire, Water, Earth, Divine, Evil**, etc.  
  - Elements grant bonus effects, resistances, or weaknesses.  
  - Certain abilities may change depending on the pet’s element.  

- **Pet Inventory** 🎒 → Pets can carry items for their owner.  
  - Configurable inventory size per pet or per tier.  
  - Useful for gathering, looting, or farming companions.  

- **Mount System** 🐎 → Some pets can grow or transform into mounts.  
  - Riding abilities: flying, swimming, sprinting, or teleporting.  
  - Balanced so not all pets are rideable (configurable per pet type).  

- **Tier & Rarity System** 🌟 → Pets can be classified as **Common, Rare, Epic, Legendary**, etc.  
  - Rarity defines base stats, unique skins, and ability strength.  
  - Higher rarity pets may unlock special effects or abilities.  

- **Field Effect System** 🌿🌋🌊 → Pets gain bonuses or altered abilities when in certain environments.  
  - Example: Fire pets gain stronger damage in Nether-like areas, Water pets heal faster near rivers.  
  - Field effects encourage strategic use of pets depending on terrain.

---

# Extra Content 📝

- Highly modular: designed so developers can extend races, skins, abilities, or rune systems without breaking core mechanics.  
- Database-driven: ensures persistence across sessions, with scalable design ready for both small servers and large networks.  
- Customizable configs: admins can tweak balance, visuals, and limits directly from config files.  
- Optional integrations: compatible with other plugins for expanded features (e.g., cosmetic systems, economy, leaderboards).  

---

👉 More details available on the official [`website`](https://mcengine-website.github.io/pet/) 🌐
