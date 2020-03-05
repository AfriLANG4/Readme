# English to Yoruba

Author: Oluwole Akinola
## Data

	- The JW300 Word English-Yoruba dataset.

## Model

- Default Masakhane Transformer translation model.
- [Link to google drive folder with models](https://drive.google.com/open?id=19hSc8eNY6iXy3rxHmicrFCRRlSaQIxIx)

## Analysis

TO DO

Example 1
```sh
	Source:     He is the Source of life , the One giving it as an undeserved gift through Christ .
	Reference:  Òun ni Orísun ìyè , Ẹni tí ń fi ìyè fúnni gẹ́gẹ́ bí ẹbùn tí a kò lẹ́tọ̀ọ́ sí nípasẹ̀ Kristi .
	Hypothesis: Òun ni Orísun ìwàláàyè , Ẹni tó fún un ní ẹ̀bùn ọ̀fẹ́ nípasẹ̀ Kristi .
```

Example 2
```sh
	Source:     Now I had to find a legitimate line of work .
	Reference:  Torí náà , mo ní láti wá iṣẹ́ gidi .
	Hypothesis: Ní báyìí , mo ti wá rí i pé iṣẹ́ tó bójú mu ni .
```

Example 3
```sh
	Source:     Do I value material things more than my relationship with Jehovah and with people ?
	Reference:  Ṣé àwọn nǹkan tara ló jẹ mí lógún jù àbí àjọṣe mi pẹ̀lú Jèhófà àtàwọn èèyàn ?
	Hypothesis: Ṣé mo mọyì àwọn nǹkan tara ju àjọṣe mi pẹ̀lú Jèhófà àti pẹ̀lú àwọn èèyàn lọ ?
```

Example 4
```sh
	Source:     He has far more experience and stamina than you do , but he patiently walks near you .
	Reference:  Ẹni tẹ́ ẹ jọ ń lọ yìí mọ ọ̀nà yẹn dáadáa .
	Hypothesis: Ó ní ìrírí tó pọ̀ ju ti tẹ́lẹ̀ lọ , ó sì ní okun ju bó o ṣe ń ṣe , àmọ́ ó ń fi sùúrù rìn nítòsí rẹ .
```

# Results

Tokenization | BLEU dev | BLEU test
--- | --- | ---
BPE| 29.15 | 34.90
