
# IAM Splitting

[The IAM Handwriting Database](https://fki.tic.heia-fr.ch/databases/iam-handwriting-database) 
contains forms of handwritten English text which can be used to train and test handwritten 
text recognizers and to perform writer identification and verification experiments.

During research of HTR task we faced some difficulties with comparing results using IAM database.
After some investigations we untangled the thread and discovered that some authors of papers 
compared results using different distributions. 
So we would like to share found splittings of IAM database.

| Split     | Train     | Valid     | Test      |
| :---:     | :---:     | :---:     | :---:     |
| IAM-A     | 6161      | 966       | 2915      |
| IAM-B     | 6482      | 976       | 2915      |
| IAM-C     | 6161      | 940       | 1861      |
| IAM-D     | 9652      | 1840      | 1861      |



## Related Work
If you have found any paper/work with these splittings of IAM, 
we are glad to see issues with links on work for adding information in this section. Thank you :)

| Name                                                                                                          | Splitting        |
| :---                                                                                                          | :---:            |  
| [Evaluating sequence-to-sequence models for handwritten text recognition.](https://arxiv.org/abs/1903.07377)  | IAM-A            |   


## Repo Authors & Contacts:

- Mark Potanin
- [Alex Shonenkov](https://www.kaggle.com/shonenkov)
- [Maxim Novopoltsev](https://github.com/maximazzik)
- Denis Dimitrov
- [Denis Karachev](https://github.com/thedenk/)

## Thanks

Thanks a lot Théodore Bluche for publishing [this resource](http://www.tbluche.com/resources.html) with IAM-B splitting and
[Joan Puigcerver](https://github.com/jpuigcerver) for publishing IAM-A splitting [here](https://github.com/jpuigcerver/Laia/tree/master/egs/iam/data/part/lines/aachen). 