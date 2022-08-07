# Southern Han Chinese Genome Assembly

The Han1 reference genome is a reference quality genome of an individual of Southern Han Chinese (population code: CHS).

This repository contains links to the Southern Chinese Han gapless genome assembly and whole genome annotation. Han1 is an assembly of an individual from Personal Genome Project codename HG00621. This repository has the initial version 1.0 assembly.

---

<br/>

## Version 1 (August 06 2022)

The released assembly and annotation for the version 1 is available at these locations:

#### Assembly: 
* [Han1_v1.2.fasta](https://bit.ly/3JylfV3)  (ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Han1/v1.0/Assembly/Han1_v1.2.fasta)

#### Annotation: 
* [Han1_v1.3.gff3](https://bit.ly/3vMnqP3)  (ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Han1/v1.0/Annotation/Han1_v1.3.gff3)

---

<br/>

## Idiogram

The data for the Han1 genome was generated and made publicly available by the Human Pangenome project (https://github.com/human-pangenomics/hpgp-data), which in turn used data from the 1000 Genomes Project and the Genome In A Bottle (GIAB) sample collections. The individual is identified as HG00621 in these collections.

The chromosome sequences for the Han1 reference genome contain bases encoded in uppercase and lowercase letters. The uppercase letters represent sequence that originated from the Han1 de novo assembled contigs, and the lowercase bases represent sequence that we took from the T2T consortium CHM13 version 1.1 genome assembly augmented with the complete Y chromosome from HG002, to fill intra-contig gaps in the chromosome sequences.

In the idiogram below, the regions in red were assembled from HG00621, and regions in light pink are sequences inserted from CHM13. The figure was created using ideogram.js (https://github.com/eweitz/ideogram).

![alt text](https://github.com/JHUCCB/ChineseHanSouthGenome/blob/main/Han1_chromosomes.png)

---

<br/>

## Statistics for Version 1.0 (August 06 2022)
|Chromosome|CHM13 #contigs|CHM13 size|Han1 #contigs|Han1 size| Non-HG00621 (inserted from CHM13) sequence| Han1 size / CHM13 size |
|---|---|---|----|----|----|----|
|chr1|1|248,387,328|1|249,525,787|119,184|1.00458|
|chr2|1|242,696,752|1|242,739,747|2,482,037|1.00018|
|chr3|1|201,105,948|1|200,211,729|377,991|0.995553|
|chr4|1|193,574,945|1|192,045,028|518,393|0.992097|
|chr5|1|182,045,439|1|181,667,637|494,129|0.997925|
|chr6|1|172,126,628|1|170,861,069|314,798|0.992648|
|chr7|1|160,567,428|1|160,865,769|107,243|1.00186|
|chr8|1|146,259,331|1|145,880,131|791,768|0.997407|
|chr9|1|150,617,247|1|148,018,047|35,504,706|0.982743|
|chr10|1|134,758,134|1|135,316,043|585,347|1.00414|
|chr11|1|135,127,769|1|135,129,219|874,841|1.00001|
|chr12|1|133,324,548|1|134,132,185|102,971|1.00606|
|chr13|1|113,566,686|1|111,903,191|10,782,722|0.985352|
|chr14|1|101,161,492|1|101,435,482|5,090,291|1.00271|
|chr15|1|99,753,195|1|101,210,777|12,429,469|1.01461|
|chr16|1|96,330,374|1|95,412,483|13,280,238|0.990471|
|chr17|1|84,276,897|1|83,450,189|1,080,955|0.990191|
|chr18|1|80,542,538|1|78,996,361|210,798|0.980803|
|chr19|1|61,707,364|1|61,978,944|1,089,081|1.0044|
|chr20|1|66,210,255|1|65,189,243|963,587|0.984579|
|chr21|1|45,090,682|1|45,827,290|5,613,897|1.01634|
|chr22|1|51,324,926|1|50,610,422|5,397,082|0.986079|
|chrX|1|154,259,566|1|154,227,164|7,056,525|0.999790|
|chrY|1|62,460,029|1|53,057,190|146,07,629|0.849458|
|chrM|1|16,569|1|16,571|0|1.000121|
|Total|25|3,117,292,070|25|3,099,707,698|119875682|0.994359|
