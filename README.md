This repository provides code for ML analysis of complete intersection Calabi-Yau (CICY) manifolds.

The datasets used are the following:
- CICY 3-folds
    - ["original" dataset](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3o.README): [hdf](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3o.h5), [json](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3o.json.gz)
    - ["favorable" dataset](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3f.README): [hdf](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3f.h5), [json](http://www.lpthe.jussieu.fr/~erbin/files/data/cicy3f.json.gz)

Information on the initial authors and URL of the datasets can be found in the README files linked by clicking on the dataset name. For simplicity, the datasets have been converted to simpler formats. Moreover, they contain additional features with respect to the initial datasets.

The code is used for the following papers:
- HE, Riccardo Finotello: [arxiv:2007.13379](https://arxiv.org/abs/2007.13379), [arxiv:2007.15706](https://arxiv.org/abs/2007.15706)

The code relies on the package [mltools](https://github.com/melsophos/mltools) which I created for my own use: it is automatically downloaded and can be found on Github. I don't guarantee forward compatibility.
