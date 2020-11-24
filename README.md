# Plotting_Poetry2020

This repository includes complementary materials of our paper for Plotting Poetry Proceedings: Hernández-Lorenzo, L.; De Sisto, M., Pérez, Á.; De la Rosa, J.; Ros, S.; González-Blanco, E.: "Quantitative metrical automatic analysis ofSpanish Poetry with Rantanplan: a first approach".

## Corpus

The corpus used in this study includes four Early Modern Spanish poets, namely Garcilaso de la Vega (1503-1536), Fernando de Herrera (1534-1597), Luis de Góngora (1561-1627) and Lope de Vega (1562-1635). The poems of each author are available in this repository, with the exception of Fernando de Herrera, whose texts were extracted from Laura Hernández's unpubished dissertion (Hernández-Lorenzo 2020). 

The texts are offered in three versions:

- An untagged (plain text) version of the corpus is included in the "corpora" folder.

- The automatically annotated version with stress positions is included in the "stress_annotation" folder. This one does not include the text of the poems, but only stress positions detected by Rantanplan (De la Rosa et al., 2020). Stress positions are marked by a number corresponding to the syllable order in the verse.

- The final version of the texts has been automatically annotated with stress positions and stanzas. It does not include the text of the poem. Also, as it was the version used in stylo (Eder et al., 2016), stress positions are marked using a special notation, which can be find at "Notatio_for_stress_positions.csv".

The corpus used for Garcilaso was scrapped from Wikipedia: https://es.wikisource.org/wiki/Autor:Garcilaso_de_la_Vega (accessed: 24/11/2020)

The corpus used for Góngora is the undoubted section of gongocorpus, available at: https://github.com/linhd-postdata/gongocorpus (accessed: 24/11/2020)

The corpus used for Lope de Vega was extracted from Biblioteca Virtual Miguel de Cervantes: http://www.cervantesvirtual.com/obra-visor/poesias-liricas--0/html/ff775820-82b1-11df-acc7-002185ce6064.html (accessed: 24/11/2020)

## Complete stanza results

The complete stanza results after applying Rantanplan on the complete poetic works by Garcilaso, Herrera, Góngora and Lope de Vega are collected in "stanza-results.csv". They include a list of 47 stanza types, from which a total of 27 were identified in, at least, one of our authors. Numbers correspond to relative values on percentages, calculated using the absolute values of each detected stanza and the total number of identified stanzas per author.
