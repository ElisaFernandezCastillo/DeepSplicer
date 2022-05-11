# Deep Splicer

Deep Splicer is a deep learning model based on convolutional neural networks (CNN) for the identification of splice sites in the genomes of humans and other species.
It was constructed and evaluated using the human genome (*Homo sapiens*) and was additionally assessed using other species’ genomes to identify how well a model trained on the human genome can generalize to other species since the objective is to use this model as a first-line annotation tool for newly sequenced genomes. The genomes of other species that were used to evaluate Deep Splicer were from *Mus musculus*, *Danio rerio*, *Drosophila melanogaster*, *Arabidopsis thaliana* and *Caenorhabditis elegans*.

To run Deep Splicer, clone the repository using:

```
git clone https://github.com/ElisaFernandezCastillo/DeepSplicer.git
```

Run the code in `Deep_Splicer.ipynb` following the order of the execution cells (from top to bottom) using a platform like Jupyter Notebook or Google Colaboratory. 

Alternatively, the Keras model can be loaded using the `deep_splicer.h5` file located on the `models` directory following this example: 

```
from keras.models import load_model
model = load_model("deep_splicer.h5")
```
