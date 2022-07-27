# Hunspell CY

Fersiwn wedi'i ddiweddaru o'r fersiwn Cymraeg o wirydd sillafu Hunspell. Mae'n cynnwys cannoedd o eirffurfiau ychwanegol gan gynnwys geirfa newydd fel 'llywodraethiant', 'atgyfeirio' a 'rhianta'.


*An updated version of the Welsh version of the Hunspell spellchecker. It includes hundreds of additional wordforms, including  'llywodraethiant', 'atgyfeirio' and 'rhianta'*

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
