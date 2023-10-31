# Hunspell CY

Fersiwn wedi'i ddiweddaru o'r fersiwn Cymraeg o wirydd sillafu Hunspell. Mae'r diweddariad yn cynnwys ffurfiau cysefin ychwanegol (gan gynnwys ‘actiwari’, ‘biodreulio’ a ‘seiberfwlio’) yn ogystal â 98 enw lle rhyngwladol ychwanegol (megis 'Irac'). Mae'r fersiwn newydd hwn hefyd yn delio gyda gogwyddeiriau Cymraeg yn well.


*An updated version of the Welsh version of the Hunspell spellchecker. The update includes additional headword forms (including 'actiwari’, ‘biodreulio’ a ‘seiberfwlio’), and also includes 98 additional international placenames (such as 'Irac'). This version also deals with clitics more effectively.*

I'w ddefnyddio o fewn eich cod:

*To use in your code:*

```
pip install hunspell
```

yna

*then*

```
import hunspell


cy_speller = hunspell.HunSpell('/usr/share/hunspell/cy_GB.dic', '/usr/share/hunspell/cy_GB.aff')
word = "kamsillafiad"
cy_speller.spell(word)

>>> False
```

Am ragor o fanlion, gweler:

*For more details, see:*

https://github.com/blatinier/pyhunspell

Ariannwyd y diweddariad hwn gan Lywodraeth Cymru.

*This update was funded by the Welsh Government.*
