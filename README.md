# Creation and Analysis of an International Corpus of Privacy Laws

Sonu Gupta, Ellen Poplavska, Nora O’Toole, Siddhant Arora, Thomas Norton, Norman Sadeh, Shomir Wilson

## Abstract

The landscape of privacy laws and regulations around the world is complex and ever-changing. National and super-national laws, agreements, decrees, and other government-issued rules form a patchwork that companies must follow to operate internationally. To examine the status and evolution of this patchwork, we intro- duce the Government Privacy Instructions Corpus, or GPI Corpus, of 1,043 privacy laws, regulations, and guidelines, covering 182 jurisdictions. This corpus enables a large-scale quantitative and qualitative examination of legal foci on privacy. We examine the temporal distribution of when GPIs were created and illustrate the dramatic increase in privacy legislation over the past 50 years, al- though a finer-grained examination reveals that the rate of increase varies depending on the personal data types that GPIs address. Our exploration also demonstrates that most privacy laws respectively address relatively few personal data types, showing that comprehen- sive privacy legislation remains rare. Additionally, topic modeling results show the prevalence of common themes in GPIs, such as finance, healthcare, and telecommunications.

## Government Privacy Instructions (GPI) Corpus 

The corpus metadata is made available under a Creative Commons Attribution-NonCommercial-ShareAlike 2.0 Generic license (CC BY-NC-SA 2.0). Inquiries about commercial licensing should be directed to Shomir Wilson (shomir@psu.edu).

The corpus can be directly downloaded from https://usableprivacy.org/static/data/gpi_corpus_v1.0_2022-06-20.zip

This corpus contains a collection of government privacy instructions (“GPI”s: e.g., laws, guidelines, orders, etc.) from around the world, mostly issued by national-level governments, but also occasionally from super-national organizations or subnational entities. They were manually gathered from the world wide web by members of the research team between 1860 and 2020. Researchers sought guidance from several law information websites, as represented by the URLs in the Document Source column as well as the Starting Source column.

A .csv file contains the metadata for the corpus: this is a large table with information about each GPI, and each GPI is provided in multiple formats, including translations to English when possible. Some translations of GPIs to English were found on the web, and some were created by the researchers using automated online tools. The reliability of translations in the dataset is not guaranteed.

The corpus download contains the following subdirectories:

-	[corpus]: Contains the contents of the entire corpus and related documents.
    -	[laws]: Contains downloadable versions  of all of the documents used within the corpus and for data analysis.
        -	[downloaded_files]: Contains the PDF versions of all of the documents used within the corpus. The documents in this file type were not utilized for data analysis.
            -	[english_pdf_files]: All PDF documents in the English language.
                -	[english_translated_pdf_files]: All PDF documents that were not originally in English and later translated to English using a third party translating machine. 
                -	[original_english_pdf_files]: All PDF documents that were originally in English.
            -	[non_english_pdf_files]: All PDF documents that were not originally in English and contained language in its original language provided by the starting source.
        -	[plain_text_files]:  Contains the TXT versions of all of the documents used within the corpus. The documents in this file type were utilized for data analysis.
            -	[english_text_files]: All TXT documents in the English language.
                -	[english_translated_text_files]: All TXT documents that were not originally in English and later translated to English using a third party translating machine. 
                -	[original_english_text_files]: All TXT documents that were originally in English.
            -	[non_english_text_files]: All TXT documents that were not originally in English and contained language in its original language provided by the starting source.
    -	[other]: Contains any relevant resources created by the research team that was not a document used within the Government Privacy Instructions Corpus.

If you use the dataset for research, you should cite the following paper:

```latex
@article{gupta2022creation,
  title={Creation and Analysis of an International Corpus of Privacy Laws},
  author={Gupta, Sonu and Poplavska, Ellen and O'Toole, Nora and Arora, Siddhant and Norton, Thomas and Sadeh, Norman and Wilson, Shomir},
  journal={arXiv preprint arXiv:2206.14169},
  year={2022}
}
```
