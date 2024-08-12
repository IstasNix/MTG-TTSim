# MTG-TTSim
Files for playtesting MTG Decks in Tabletop Simulator. Multiple formats of MTG are supported, with most card images being pulled from the usual suspect, Scryfall.
## deck
_Includes decklist JSON files, sorted by format._
### commander
Commander has its own banlist, and consists of decks built around a legendary creature which you will have ready access to. Decks can only include cards or generate mana of colors which match your chosen commander's color identity. Decks cannot include duplicates of any card which is not a basic land. Due to this singleton nature, most decks have multiple win conditions.<br>
_These decks will generally import the commanders as oversized cards, the main deck in normal fashion, and separately include any necessary tokens. If a deck has multiple commanders, both will be separated from the main deck and oversized._
### legacy
Legacy has its own banlist, and does not exclude any sets. Decks include a minimum of 60 cards, and may also include a separate sideboard with up to 15 cards. No more than 4 copies of any card which is not a basic land can be included.<br>
_These decks will generally import the main deck, a separate sideboard, and any necessary tokens._
### modern
Modern has its own banlist, and includes all sets from 8th Edition forward. Decks include a minimum of 60 cards, and may also include a separate sideboard with up to 15 cards. No more than 4 copies of any card which is not a basic land can be included.<br>
_These decks will generally import the main deck, a separate sideboard, and any necessary tokens._
## model
_Includes model JSON files, sorted alphabetically._
## texture
_Includes asset PNG files, sorted by type and purpose._
### card
All card assets which are not pulled from Scryfall live here.<br>
_This includes alternate card backs, and custom card replacements._
### model
All textures which are to be applied to custom models (or the TTS environment) live here.<br>
_This includes textures for various counters, the tabletop itself, and format-specific miscellania._
