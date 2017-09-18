Script for decoding Lingea Dictionary (.trd) file. Result is 

```
<header>

\t

<definition>
```

 file, convertible easily by stardict-editor (or by tabfile command from package stardict-tools) into native Stardict dictionary (stardict.sf.net and www.stardict.org).
To run the decoder you need a Python interpreter.

More info at the project website:
http://www.klokan.cz/projects/stardict-lingea/

Usage:
------

Download [lingea-trd-decoder.py](https://raw.githubusercontent.com/PetrDlouhy/lingea-trd-decoder/master/lingea-trd-decoder.py) (or `git clone https://github.com/PetrDlouhy/lingea-trd-decoder.git`)

Run folowing command:
```
python lingea-trd-decoder.py input.trd  > output.txt
```
