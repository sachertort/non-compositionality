# Non-compositionality
The program code – `Non-compositional.ipynb`.
If you want to run the whole code, you should just go by cell order; you also need the model `ruwikiruscorpora-superbigrams_skipgram_300_2_2018` from [RusVectōrēs](https://rusvectores.org/ru/models/besides) given files.  
If you do not want to run preprocessing and vectorizations, import all neccessary modules and then start from the section *Experiments*, but you need to download the dataset file with embeddings from [Google Drive](https://drive.google.com/file/d/1OAnH8qtXM92E4DLC77Q4oV2QmqBuE-Nh/view?usp=sharing) (GitHub forbid uploads of large files now).  
Other files:
  * `compounds_AN_top10000.csv` – the primary dataset from (Puzyrev et al. 2019)
  * `lr.csv` - expressions with scores predicted by Linear Regression (0 - totally non-compositional, 1 - totally compositional)
