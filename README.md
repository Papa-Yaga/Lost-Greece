# Lost Greece

Decyphering old Greek on lost Papyrus!
- a Project by Sergej N.

In this project we will be applying deep learning models
to create an image recognition system that can read near 
unreadable letters of old greek on papyrus. 
With a custom built layered model we hope to be able to 
read out words and letters on otherwise unreadable scrolls
if papyrus.

Data has been taken from the following Kaggle Datasets:

- https://www.kaggle.com/datasets/miswindall/al-pub-v2
- https://www.kaggle.com/datasets/katianakontolati/classification-of-handwritten-greek-letters

and consists of roughly 200.000 Images of varying stages of decayed letters aswell as some digitally handpainted ones.

Going forward the model in this repo will be improved, especially in terms of speed, by normalizing and otherwise optimizing the 
values in the images. Additionally, a recursive layer structure will be added to improve the precision further. If time allows, 
the model will also be upgraded to not only identify individual letters but full letter structures on paper, recognizing both
the letter and its position on script.
