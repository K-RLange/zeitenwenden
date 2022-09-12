# Zeitenwenden
## Detecting changes in the German political discourse

This repository provides some results related to the paper:

* Lange, K.-R., Rieger, J., Benner, N. & Jentsch, C. (2022). Zeitenwenden: Detecting changes in the German political discourse. Proceedings of the 2nd Workshop on Computational Linguistics for Political Text Analysis ([CPSS](https://old.gscl.org/en/arbeitskreise/cpss/cpss-2022)). [pdf](https://old.gscl.org/media/pages/arbeitskreise/cpss/cpss-2022/workshop-proceedings-2022/254133848-1662750260/cpss-2022-proceedings.pdf).

For bug reports, comments and questions please use the [issue tracker](https://github.com/K-RLange/zeitenwenden/issues).

##Structure
The results are divided by the number of topics used for the RollingLDA object. The results are presented for a look-back-window of 4 and a mixture parameter of 0.9,...,0.95. 

Further results using this method for a different data set can be found in [the corresponding repository](https://github.com/JonasRieger/topicalchanges). The change detection method is based on

* Rieger, J., Lange, K.-R., Flossdorf, J. & Jentsch, C. (2022). Dynamic change detection in topics based on rolling LDAs. Proceedings of the [Text2Story'22 Workshop](https://text2story22.inesctec.pt/). CEUR-WS 3117, pp. 5-13. [pdf](http://ceur-ws.org/Vol-3117/paper1.pdf).
