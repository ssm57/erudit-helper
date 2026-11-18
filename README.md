# Эрудит-подсказчик

A move finder for the Russian word game Эрудит that runs entirely in the browser and works offline.

**Open it:** https://ssm57.github.io/erudit-helper/

On iPhone (Chrome or Safari): open the link once while online, tap Share, then "Add to Home Screen". It then opens from its own icon with no internet connection.

- **Screenshot:** take a screenshot in the game and tap «Скриншот». The board and your tiles are read from the image on the phone (no upload anywhere), tiles placed this turn but not yet played go back to your hand, and moves are found right away. Letters it is unsure of get a red frame; fixing one teaches it, so reading improves with use.
- Or enter the board by tapping squares and typing; enter your tiles on the rack; press «Найти ходы».
- Moves are ranked by score using the standard board premiums and Эрудит letter values (editable in «Настройки»), with a 15-point bonus for using all 7 tiles.
- Words the game rejects can be excluded with one tap; missing words can be added in settings.

The noun list comes from [Russian-Nouns](https://github.com/Harrix/Russian-Nouns) by Anton Sergienko (MIT License, see `DICTIONARY-LICENSE.md`).
