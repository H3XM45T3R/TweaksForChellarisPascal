# Complete list of tweaks by folder and file:

## common
### ascension_perks
- zzzzzzzzzzz_crisis
	- Allow Become The Crisis for anyone
### buildings
- zzzz_ancient_refinery
	- Limit Ancient Refinery to 3 per empire
- zzzzzz_enable_technocorp_building
	- Enable branch building for Scientific Corporatism
	- Add trade value modifier for Outsourced R&D to branch buildings
### bypass
- zz_catapult
	- Allow use of Quantum Cat if you don’t have the tech yourself
### casus_belli
- zzz_cb
	- Remove notifications for crisis CB
	- Remove TW CBs for Assimilators
	- Allow Galatron CB for Assimilators
### defines
- zzz_defines
	- Change galcome cooldowns
	- Change min and max trade deal length
	- Remove 1/species rights change cooldowns
	- Cap upkeep reduction
	- Reduced maximum naval cap
### diplomatic_actions
- zzzz_diplo
	- Allow Assimilators to have rivals
	- Allow Inwards Perfection/Apathetic more diplo actions with certain traditions
	- Disallow scion overlord to close borders to its subject
### edicts
- zzzz_veru_event_edicts
	- Disable the vassal management edict
### game_rules
- zzz_xeno_compat
	- Move check for xeno compat here instead of inside the AP
- zzz_allow_claim
	- Allow Assimilators to claim and be claimed
### governments
**civics**
- zzzz_pompous_purists
  - Allow Pompous Purists to use the Scion origin
- zzzz_origins
  - Allow Infesting Hive for non-Devouring Swarm
  - Allow 04 Origin for hives
- zzzz_civics
  - Disallow Alpha Directive for Servitors
### inline_scripts
**traits**
- inline_aquatic_trait_effects
  - Effects for aquatic traits

**jobs/resources**
  - inline_evolved_tec_hive_mindflayers
    - Change production for Livestock with Mindflayers civic

**buildings/modifiers**
  - inline_researchbureau_trade_value
        - Trade value modifiers for Outsourced R&D branch buildings
### megastructures
- zz_disable_orbital_rings
	- Disable orbital rings
### policies
- zzzzzz_policies
	- Allow aggressive interference for Exploration Protocol
	- Allow animosity diplo stance for subjects
### pop_categories
- zzzzzzzzzzzzzzzzzzzzzz_popcats
	- Compat for species diversity and evolved
### pop_jobs
- zz_mental_slave_job
	- Change production for Mental Slaves
- zzz_lith_anglers
	- Add Reef Miner production from Anglers councillor
### resolutions
- zzzz_pompous_custodian
	- Allow Pompous Purists to become custodian
### technology
- zz_disable_orbital_rings
	- Disable orbital rings
- zzz_nanites
	- Scavenger bot techs are available as rare techs after reseraching neanite production
- zzzz_genetics
	- Allow genetics and cloning techs for machine empires with any organic pop
### terraform
- pd_hycean_terraform_links
	- Change eco cat of hycean terraform to ocean terraforming
### traits
- zz_evolved_feature_traits
	- Disable advanced aquatic trait
- zz_evolved_robotic_traits
	- Changed unadapatable to -20% hab
	- Changed machine aquatics effect
- 00_species_traits_basic_characteristics
	- Changed aquatics trait effect
### scripted_triggers
- 00_machine_genetics_scripted_trigger
	- Check if there’s any organic species for machines
- 00_aquatics_trait_scripted_triggers
	- Check Planet Classes for overhauled aquatic trait
- zzzzzzzzzzzzzzzzz_scripted_triggers
	- Make Assimilators not be considered a TW country
	- Allow normal empire necrophages from phaging livestock
### solar_system_initializers
- void_visitors_init
	- Some stuff from serente
- !!_lgates
	- Add nanite words with nanite deposits to L-Gate systems
### war_goals
- zz_war_goals
	- Disable Assimilation war goals

## events
- !protoworld_finish
  - Add Exotic Gas deposits to toxic protoworlds
- !pd_startgame
  - Disable PD startup planet change event in MP
 
## gfx
### interface/icons/buildings
- building_tec_private_patents_initiative
  - Building icon for Scientific Corporatism branch building

## localisation
### replace
- zzz_replace_aquatics_l_english
  - New aquatics trait description
- zz_replace_evolved_l_english
  - Change Mindflayers description to match new production
