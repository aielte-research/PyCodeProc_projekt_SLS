# PyCodeProc_projekt_SLS
önálló projekt 3 - Sisák Sándor

A modell kódrészletekhez multilabel klasszifikációval rendel stackoverflow címkéket.

A PyProcProjekt_adatkinyeres.ipynb a kaggle.com/datasets/stackoverflow/pythonquestions forrásból dolgozik. A kérdések címkéit párosítja a válaszokban található kódrészletekkel. (Ennek eredménye PyCodes.json-ként lesz mentve)

A PyProcProjekt_modell.ipynb a PyCodes.json címkéit one-hot vektorokká alakítja, a kiválogatott kódrészleteket tokenizálja, végül klasszifikációt tanul.

TODO:\\
A PyProcProjekt_adatkinyeres.ipynb még bőven tele van szeméttel.\\
A PyProcProjekt_modell.ipynb meg nem működik :))
