
# IAM Splittings

[The IAM Handwriting Database](https://fki.tic.heia-fr.ch/databases/iam-handwriting-database) 
contains forms of handwritten English text which can be used to train and test handwritten 
text recognizers and to perform writer identification and verification experiments.

During research of HTR task we faced some difficulties with comparing results using IAM database.
After some investigations we untangled the thread and discovered that some authors of papers 
compared results using different distributions. 
So we would like to share all found splittings of IAM database.

| Split     | Train     | Valid     | Test      |
| :---:     | :---:     | :---:     | :---:     |
| IAM-A     | 6161      | 966       | 2915      |
| IAM-B     | 6482      | 976       | 2915      |
| IAM-C     | 6161      | 940       | 1861      |
| IAM-D     | 9652      | 1840      | 1861      |



## Authors & Contacts:

- Mark Potanin
- [Alex Shonenkov](https://www.kaggle.com/shonenkov)
- [Denis Karachev](https://github.com/thedenk/)
- [Maxim Novopoltsev](https://github.com/maximazzik)
- Denis Dimitrov

## Thanks

Thanks a lot Théodore Bluche for publishing [this resource](http://www.tbluche.com/resources.html) with IAM-B splitting. 