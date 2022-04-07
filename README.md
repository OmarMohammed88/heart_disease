# heart_disease
## ToDo


All experiments have been evaluated on test set 
Model type| F1-score |Done
------------ | ------------- |-----------|
[microsoft(med-bert)](https://huggingface.co/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext)|91|✔️|
[biobert](https://github.com/dmis-lab/biobert/)+charBert |92.7|✔️
bertConfig+BertChar|**93.66**| ✔️
bertConfig+BertChar+focalLS|93.45| ✔️
microsoft+focalLs| 91.05 |✔️
microsoft+charBert|0.9128|✔️
