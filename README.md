# IsiZulu News (articles and headlines) and Siswati News (headlines) Corpora - za-isizulu-siswati-news-2022


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7193346.svg)](https://doi.org/10.5281/zenodo.7193346)

### About Dataset

Dataset for both isiZulu news (articles and headlines) and Siswati news headlines. Process included scraping the data from internet, from Isolezwe news website http://www.isolezwe.co.za and public posts from the SABC news LigwalagwalaFM Facebook page https://www.facebook.com/ligwalagwalafm/ respectively.

The obtained datasets are isiZulu news articles, isiZulu news headlines, and Siswati news headlines. 

Post data collection the datasets were then sent to annotators, and they were sent back after the annotation process. The datasets contain special characters, some English words and characters that are not ASCII encoded which must be removed prior to model training. The aim of these three datasets is to create a baseline news categorisation model for the two South African low resources languages i.e. isiZulu and Siswati. 

For categorisation, we use high level [IPTC NewsCodes](https://iptc.org/standards/newscodes/) as categories. You can view the news categories here [data/news-categories-iptc-newscodes.csv](data/news-categories-iptc-newscodes.csv)

The datasets were found to have class categories with very few observations, hence the class categories which have less than 35 observations were removed for isiZulu and less 6 observations for Siswati. 

The dataset has both full category data as well as reduced category data.

Please see the [data-statement.md](data-statement.md) for full dataset information.

## Online Repository link

* Link to the DOI data repository - [Zenodo Data Repository](https://doi.org/10.5281/zenodo.7193346)
*  
## Authors

* **Andani Madodonga** 
* **Vukosi Marivate** - [@vukosi](https://twitter.com/vukosi)
* **Matthew Adendorff**

See also the list of [contributors](https://github.com/dsfsi/za-isizulu-siswati-news-2022/contributors) who participated in this project.

## Citation

**Citation:**  Madodonga, A., Marivate, V., & Adendorff, M. (2023). Izindaba-Tindzaba: Machine learning news categorisation for Long and Short Text for isiZulu and Siswati. Journal of the Digital Humanities Association of Southern Africa, 4(01). [https://doi.org/10.55492/dhasa.v4i01.4449](https://doi.org/10.55492/dhasa.v4i01.4449)

## License

Data is Licensed under CC 4.0 BY SA

Code is Licences under MIT License.
