# adr-transformer-IOB-Schema

<p> Algorithm for Doccano data transformation for ** CoNLL 2003 ** or ** IOB ** <br> </p>

Before implementing the Algorithm CRF(Conditional Random Fields) it is necessary to classify the entities, in this project used: <br/>
<img align="center" alt="MongoDB" height="60" width="130" src="https://raw.githubusercontent.com/doccano/doccano/master/docs/images/logo/doccano.png">

<p>Doccano software was used to classify entities manually, a technique of Natural Language Processing, we created two entities called <strong>DRUG (Medicine)</strong> and <strong>ADR (Adverse Drug Reaction)</strong>.
Manual classification was applied to 5.000 tweets, of which only 750 contained both entities simultaneously in the tweet.
The manually classified entities were exported to JSONL (Text Label) format.</p>

Programming language used:

<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" target="_blank"></a> 

Stored in NoSQL database:

<a href="https://www.mongodb.com/pt-br" target="_blank"><img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" target="_blank"></a> 

#
This is part 2 of 5 of the course completion work. Developed by <a href="https://github.com/bpaixao">Beatriz Paixão</a> and <a href="https://github.com/katheleen-gregorato">Katheleen Gregorato</a>. See our publication in <strong>CONICT - IFSP</strong> at: https://bit.ly/3IsqULo
