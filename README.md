# adr-transformer-IOB-Schema

<p> Algorithm for transforming Doccano data into ** CoNLL 2003 ** or ** IOB ** </p>

<p> Before implementing the CRF (Conditional Random Fields) algorithm, it was necessary to classify the entities stored in the NoSQL database<br/>

<p>The Doccano software was used to classify the entities manually, using a Natural Language Processing technique. We created two entities called <strong> DRUG (Drug) </strong> and <strong> ADR (Adverse Drug Reaction)</strong>. The manual classification was applied to 5,000 tweets, of which only 750 contained both entities simultaneously in the tweet. The manually classified entities were exported to JSONL (text tag) format.
</p>
<img align="center" alt="MongoDB" height="60" width="130" src="https://raw.githubusercontent.com/doccano/doccano/master/docs/images/logo/doccano.png">
<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" target="_blank"></a> 
<a href="https://www.mongodb.com/pt-br" target="_blank"><img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" target="_blank"></a> 

#
This is part 2 of 5 of the course completion work. Developed by <a href="https://github.com/bpaixao">Beatriz Paixão</a> and <a href="https://github.com/katheleen-gregorato">Katheleen Gregorato</a>. See our publication on <strong>CONICT - IFSP</strong> at: https://bit.ly/3IsqULo
