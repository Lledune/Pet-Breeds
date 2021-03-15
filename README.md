# Pet breeds classifier 

Deep learning classifier for pet breeds (dogs and cats). 38 categories are taken in account for the classification. 

Accuracy of over 90% on the test set.

The deep neural network is based on densenet169 architecture and transfer learning was used. 

The categories are : 

['Abyssinian', 'Bengal', 'Birman', 'Bombay', 'British_Shorthair', 'Egyptian_Mau', 'Maine_Coon', 'Persian', 'Ragdoll', 'Russian_Blue', 'Siamese', 'Sphynx', 'american_bulldog', 'american_pit_bull_terrier', 'basset_hound', 'beagle', 'boxer', 'chihuahua', 'dutch_long', 'english_cocker_spaniel', 'english_setter', 'german_shorthaired', 'great_pyrenees', 'havanese', 'japanese_chin', 'keeshond', 'leonberger', 'miniature_pinscher', 'newfoundland', 'pomeranian', 'pug', 'saint_bernard', 'samoyed', 'scottish_terrier', 'shiba_inu', 'staffordshire_bull_terrier', 'wheaten_terrier', 'yorkshire_terrier']

I am using oxfords PETS dataset as a baseline, and enhanced dataset to create one new category : "dutch_long" => Long-haired dutch shepherd, my own dog's breed :)

Project available here for testing : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lledune/Pet-Breeds/main?urlpath=%2Fvoila%2Frender%2Fapp.ipynb)

(The loading can take a few minutes as this is a free server that needs to build a docker image before starting).
