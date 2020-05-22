# Hate speech dataset from a white supremacist forum

`
Disclaimer: The number of files available in this repository may be slightly different to the numbers reported in the paper due to some last minute changes and additions. But the overall content distribution and conclusions should remain unchanged. 
`

These files contain text extracted from Stormfront, a white supremacist forum.
A random set of forums posts have been sampled from several subforums and split into sentences.
Those sentences have been manually labelled as containing hate speech or not, according to certain annotation guidelines.
 
More information about the dataset and the guidelines can be found in the following article [[pdf](https://www.aclweb.org/anthology/W18-51.pdf)]:
 
*O. de Gibert, N. Perez, A. García-Pablos, M. Cuadros. Hate Speech Dataset from a White Supremacy Forum. In: Proceedings of the 2nd Workshop on Abusive Language Online (ALW2), pp. 11-20, 2018.*
 
If you use any of the provided material in your work, please cite us as follows:

```
@inproceedings{gibert2018hate,
    title = "{Hate Speech Dataset from a White Supremacy Forum}",
    author = "de Gibert, Ona  and
      Perez, Naiara  and
      Garc{\'\i}a-Pablos, Aitor  and
      Cuadros, Montse",
    booktitle = "Proceedings of the 2nd Workshop on Abusive Language Online ({ALW}2)",
    month = oct,
    year = "2018",
    address = "Brussels, Belgium",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W18-5102",
    doi = "10.18653/v1/W18-5102",
    pages = "11--20",
}
```

## Repository structure
 
* **all_files**: the folder that contains all the forum posts. Each file contains a sentence. The file name is formatted as commentID_sentenceNumber.txt, so the files that share the same number before the underscore pertain to the same comment.
* **sampled_train**: a balanced set of files (for "hate" and "noHate" classes) sampled from all_files, used for experiments.
* **sampled_test**: a balanced set of files (for "hate" and "noHate" classes) sampled from all_files, used for experiments.
* **annotations_metadata.csv**: this file contains the actual label for each file in the previous folders; additionally, it reports how much additional context the annotator required to make a decision over each sentence, the user id, and the subforum id (ids are just numbers that do not further identify people).

## License

The resources in this repository are licensed under the Creative Commons Attribution-ShareAlike 3.0 Spain License. To
view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/es/ or send a letter to Creative
Commons, PO Box 1866, Mountain View, CA 94042, USA.

## Contact

If you have any question or suggestion, do not hesitate to contact us at the following addresses:

* Naiara Perez: nperez@vicomtech.org
* Aitor García: agarciap@vicomtech.org
* Montse Cuadros: mcuadros@vicomtech.org

Learn more about us at http://www.speechandlanguagesolutions.com/.
