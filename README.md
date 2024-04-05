# MET-Meme: A Multi-modal Meme Dataset Rich in Metaphors
!This is the dataset for paper *<<MET-Meme: A Multi-modal Meme Dataset Rich in Metaphors>>*.  <br>
MET-Meme spans across two languages, amounting to 10039 text-image pairs with manual annotations.  <br>
**Cimages.rar** is a compressed file containing 6045 Chinese images.<br>
**Eimages.rar** is a compressed file containing 3994 English images.<br>
images can be downloaded [here](https://www.kaggle.com/datasets/liaolianfoka/met-meme)
## Introduction to Met-meme： <br>
### (1): metaphor annotation: 
>>1.metaphor occurrence : literal meme(0); metaphorical meme(1). <br>
>>2.metaphor category: complementary;text dominant;image dominant.<br>
>>3.source domain and target domain are annotated with the structure of "adj + n" or "verb + n". <br>
>>4.source modality and target modality :complementary;text dominant;image dominant. <br>
### (2):sentiment analysis:  happiness(1);love(2);anger(3);sorrow(4);fear(5);hate(6);surprise(7).<br>
### (3):intention category:  interactive(1);expressive(2);purely entertaining(3);offensive(4);other(5).<br>
### (4):offensiveness degree: non-offensive(0);slightly offensive(1);moderately offensive(2);very offensive(3).<br>
# MET-Meme's code
The code we provide can be run directly, but the pre-training process of multilingual Bert, vgg16 and resnet50 requires the reader to complete beforehand. Detailed hyperparameters are shown in our paper.
