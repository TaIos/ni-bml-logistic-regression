# Logistická regrese - kvalita odhadu [30b]

Tento týden jsme dělali logistickou regresi. V ní je laplaceovská aproximace, kde se hledá MAP odhad - na maximum aposteriorní distribuce se nasazuje gausovka. To maximum se hledá Newtonovou iterační metodou. A jako zajímavý projekt by mi přišlo zkusit porovnat:
1) více kroků Newtona (ve skriptu/jupyteru je jen jeden)
2) nějakou numerickou metodu pro hledání maxima (lze použít rovnou ze scipy)

To porovnání by bylo z hlediska rychlosti konvergence odhadů (pro srovnání mi stačí vzít MLE odhady z sklearn).
