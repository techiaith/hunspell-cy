# Hunspell CY

Fersiwn wedi'i ddiweddaru o'r fersiwn Cymraeg o wirydd sillafu Hunspell. Mae'n cynnwys cannoedd o eirffurfiau ychwanegol gan gynnwys geirfa newydd fel 'hunlun' a rhediadau berfol cyflawn ar gyfer geiriau fel 'lawrlwytho' ('lawrlwythais', 'lawrlwythiast', etc.), 'blogio' a 'hunanynysu'.


*An updated version of the Welsh version of the Hunspell spellchecker. It includes hundreds of additional wordforms, including 'hunlun' (=selfie) and full veral conjugations for words such as 'lawrlwytho' (=to download) ('lawrlwythais', 'lawrlwythiast', etc.), 'blogio' (=to blog) and 'hunanynysu' (to self-isolate).*

I'w ddefnyddio o fewn eich cod:

*To use in your code:*

```
pip install pyhunspell
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

https://github.com/blatinier/pyhunspell/wiki/Documentation
