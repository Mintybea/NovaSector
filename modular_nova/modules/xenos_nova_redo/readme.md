## Title: Nova Sector Xeno Rework

MODULE ID: NOVA_XENO_REDO

### Description:

Reworks and rebalances xenomorphs to be more in line a tgmc style of alien, especially focusing on unique abilites and lack of rclick and ranged instant hardstuns

### TG Proc/File Changes:

- MOVED:
	code\modules\mob\living\carbon\alien\larva\powers.dm > /datum/action/cooldown/alien/larva_evolve/Activate
	TO:
	modular_nova\modules\xenos_nova_redo\code\larva.dm

- MOVED:
	code\modules\mob\living\carbon\human\human_defense.dm > /mob/living/carbon/human/attack_alien
	TO:
	modular_nova\modules\xenos_nova_redo\code\human_defense.dm

### Defines:

IN: code/__DEFINES/~nova_defines/traits.dm

- TRAIT_XENO_INNATE
- TRAIT_XENO_ABILITY_GIVEN
- TRAIT_XENO_HEAL_AURA

### Master file additions

- N/A

### Included files that are not contained in this module:

- N/A

### Credits:
TGMC - Where the sprites, sound, and ideas for caste abilities came from
Those two rounds where xenos curbstomped the whole station - Inspiration for doing this in the first place
