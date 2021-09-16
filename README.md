# taxonomyclassifierCNN

I designed a toy model pipeline for classifying the taxonomic data based on convolutional neural networks and it used the taxonomic data which was generated by Sequence Evolution with the help of a phylogenetic algorithm.


Taxonomic assignment plays a key role in classifying the species in Biodiversity and evolution studies. Most of the Taxonomic assignment method was developed by the Advantage algorithm method, however, it would take a lot of computational time and data, and therefore I was designing a pipeline based on the convolutional neural networks for classifying the taxonomic data. for the testing purpose, I generate the 1000 taxonomic sequences with each have 50 sequence lengths, afterward, I labeled each taxonomic data using principal component analysis, for simplicity I labeled each taxonomic data from 0 to 3. this model was trained by taxonomic data and their label and predict on given taxonomic data.
