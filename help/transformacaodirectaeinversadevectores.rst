Transforma��o Directa e Inversa de Vectores
================================

Descri��o
-----------

Esta ferramenta usa como ficheiro de entrada um vector. O ficheiro de sa�da ser� um shapefile. A transforma��o de datum com as grelhas NTv2 pode ser efectuada na forma directa (Data nacionais antigos [Datum Lisboa / Datum Lisboa Militar / Datum 73 / Datum 73 Militar / ED50 UTM 29N] ->  PT-TM06/ETRS89) ou na forma inversa (PT-TM06/ETRS89 -> Data nacionais antigos [Datum Lisboa / Datum Lisboa Militar / Datum 73 / Datum 73 Militar / ED50 UTM 29N]).


Par�metros
----------

- ``Ficheiro de entrada [Vector]``: vector de entrada

- ``Transforma��o``: Escolher entre as formas de transforma��o disponibilizadas - [Directa] para transforma��es dos data nacionais antigos (Datum Lisboa / Datum Lisboa Militar / Datum 73 / Datum 73 Militar / ED50 UTM 29N) para o PT-TM06/ETRS89; [Inversa] para transforma��es do PT-TM06/ETRS89 para um dos data nacionais antigos (Datum Lisboa / Datum Lisboa Militar / Datum 73 / Datum 73 Militar / ED50 UTM 29N).

- ``Datum antigo``: Escolher o datum nacional antigo do ficheiro de entrada, para o caso de transforma��es na forma directa. Para transforma��es na forma inversa, esta op��o corresponde ao datum a aplicar ao ficheiro de sa�da.

- ``Grelhas NTv2 [de transforma��o de datum] a usar (Fonte)``: Escolher uma das duas grelhas NTv2 suportadas - as desenvolvidas pelo Prof. Jos� Alberto Gon�alves, da Faculdade de Ci�ncias da Universidade do Porto (FCUP), ou as produzidas pela Dire��o-Geral do Territ�rio (DGT). A DGT n�o disponibiliza grelhas para o ED50 UTM 29N, pelo que para dados nesse sistema, a transforma��o usa sempre as grelhas do Prof. Jos� Alberto Gon�alves.


Ficheiros de sa�da
-------

- ``Ficheiro de sa�da [Vector]``: vector de sa�da em formato shapefile
