# v1.5.10
- When the `Display translations` setting is on and the `Scramble for GM` setting is off, it'll show "Translated from *language*" instead of just "Translation".
- Fixed DSA5 fonts for the Premium Content.

# v1.5.9
- Added support to Shadow of the Demon Lord (thanks to [@Patrick Porto](https://github.com/patrickporto)).

# v1.5.8
- Fixed DSA5 fonts not being shown.

# v1.5.7.3
- Replaced the translation box with a horizontal line.
- Added language fonts for DSA5.

# v1.5.7.2
- Added support to Aria (thanks to [@Dilomos](https://github.com/Dilomos)).
- Added German translation (thanks to [@Nyhles](https://github.com/Nyhles)).

# v1.5.7.1
- Added support to DCC.
- Added partial support to DSA5.
- Added Japanese translation (thanks to [Touge](https://github.com/BrotherSharper)).
- Updated Spanish translation.

# v1.5.7.0
- Settings were reordered. Settings related to Languages or Chat are separated into their own menu to save space and keep things ordered.
- Added a Replace System's Languages setting, which removes every default language from the dropdown menu.

# v1.5.6.13
- Fixed an issue in Pathfinder 2e where the damage message outputted by NPCs would be translated if the Scramble on OOC chat messages setting was enabled. 

# v1.5.6.12
- Any system with languages set up as `CONFIG.SYSTEMNAME.languages` (e.g. dnd5e's is CONFIG.DND5E.languages) should show the languages without needing to make changes to the module. Adding a font to each language still requires changing the module, though.

# v1.5.6.11
- Added support to CoC7.
- Updated Spanish translation (thanks to [@lozalojo](https://github.com/lozalojo)).
- Added Czech translation (thanks to [@KarelZavicak](https://github.com/KarelZavicak)).

# v1.5.6.10
- SW5e: "Updated fonts to more closely match the languages found on Wookieepedia that have visual references." (thanks to [@whtwlf](https://github.com/whtwlf)).

# v1.5.6.9
- Added support to SW5e (thanks to [@mxzf](https://github.com/mxzf)).

# v1.5.6.8
- Fixed an issue with Tongues feature which couldn't translate languages, only be translated.
- Fixed an issue with OSE system where the default language wasn't being set properly.

# v1.5.6.7
- Text inside the Translation Box is now selectable.

# v1.5.6.6
- Added a "Hide Globe and "Translated From" text from players" so you can hide the language you're speaking on from your players.

# v1.5.6.5
- Fixed an issue with setting the Common language on WFRP4 (and possibly SWADE).

# v1.5.6.4
- Fixed an issue with the Common language not being set properly.
- Fixed an edge case where the module would throw errors when a message would be deleted faster than it would translate it.

# v1.5.6.3
- Fixed an issue with the Common language being scrambled in D&D 5e games that were using Babele.
- Improved Babele support to WFRP4 (thanks to [@sladecraven](https://github.com/sladecraven)).
- Added French translation (thanks to [@sladecraven](https://github.com/sladecraven)).

# v1.5.6.2
- Fixed an issue with the Common language not being properly shown as the default language when selecting a token.

# v1.5.6.1
- Added Babele support to WFRP4.
- Added a Toggle Runes Text on Journals. It toggles the visibility of the `Runes` text on Journals, so you have some extra space on the header.

# v1.5.6
- Added the Comprehend Languages setting. Input a Custom Language you've already set and it becomes a language that can't be spoken but can understand all languages, written or spoken.
- Added the Tongues setting. Input a Custom Language you've already set and it becomes a language that can understand all spoken languages and be understood by all actors, but can't be written.
- Added partial support to SWADE. You have to add a skill like this `Language (Name)` and it'll show up on the menu.
- Fixed the module not working with 3.5e.

![image](https://user-images.githubusercontent.com/5288872/109089668-61cd3880-76f0-11eb-88ee-57f3e2c00658.png)

# v1.5.5.1
- Added Korean translation (thanks to [https://github.com/drdwing](@drdwing)).

# v1.5.5
- Fixed Translation Box translating Common.
- Fixed Spanish translation not showing.

# v1.5.4
- Added Translation Box setting (thanks to [https://github.com/ironmonk88](@ironmonk88)). Players can now choose between showing the language's script along with a translation box or the original functionality.

# v1.5.3
- Fixed a bug that caused the addon to not load on D&D 5e.
- Added Spanish translation (thanks to [https://github.com/juanfrank](@juanfrank)).

# v1.5.2
- Added D&D 3.5e support.
- D&D 5e: Added fonts to Aarakocra, Halfling and Thieves' Cant.
- Fixed the module not downloading with the fonts and settings folders.

# v1.5
- Added localization support.
- Added support to the Tormenta20 system.
- Reduced the Journal's Rune Highlight from 0.75 to 0.25.
- Added Starfinder support. I don't play the system, so I wasn't sure which fonts would suit each language, I'm open for suggestions.