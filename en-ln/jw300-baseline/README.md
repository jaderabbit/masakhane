# English to Lingala

Author: Murhabazi B. Espoir

## Data

	- The JW300 English- Lingala.

## Model

	- Default Masakhane Transformer translation model.
	- The model can be found [here](https://drive.google.com/open?id=1w-4aejEmCVpqIAa7xYw2sJVfMLNMVeKK)

## Analysis

Example 1
```ln
    Source:     Jehovah Is Exalted
    Reference:  Yehova akumisami
    Hypothesis: Yehova atombwami
	
```

Example 2
```ln
	Source:     He goes to an Escuela Nueva , or New School , that has a flexible program designed to help children to catch up if they have to miss a few days ’ school ​ — a common occurrence , especially at harvest time .
    Reference:  Akendeke kelasi na Escuela Nueva , to eteyelo ya sika , oyo ezali na manáka ya pɛtɛɛ mpo na kosunga bana ete bázonga nsima te ata soki bazangisi kelasi na boumeli ya mwa mikolo , likambo liyaka mbala na mbala , mingimingi na ntango ya kobuka mbuma .
    Hypothesis: Azali kokende na Ecuela Nueva , to na Eteyelo ya Sika , oyo ezali na programɛ moko ya malamu mpenza oyo ebongisami mpo na kosalisa bana bázwa ekateli soki basengeli kozanga mwa mikolo , elingi koloba makambo oyo esalemaka mingi , mingimingi na eleko ya kobuka mbuma .
```

Example 3
```ln
	Source:     asked an Awake ! writer .
    Reference:  Mokomi moko ya Lamuká !
 	Hypothesis: etunaki ye ete : “ Nakosala nini ? ”
```
# Results
	- BLEU dev :   32.74
	- BLEU test :  48.64
