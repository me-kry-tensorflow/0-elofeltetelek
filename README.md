# tensor-flow mintapéldák

Feladat a projekt gyökerében lefuttatni az src/check_all.py scriptet. 
Ez létrehoz egy versions.txt file-t az adott mappában.
Ha ez a file megfelelő, akkor a github-on  az actions allatt az utolsó futás zöld.

https://docs.github.com/en/education/manage-coursework-with-github-classroom/view-autograding-results
https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-status-checks

## beüzemelés, telepítés

Utoljára tesztelve python 3.8.5 interpreterrel.

Hozzunk létre egy virtuális python környezetet, hogy ne akadjanak össze a csomagjaink más python alkalmazással!

Tamogatott (es tesztelt) python verzio: 3.8

### kozos

Ha nincs fent Visual Studio
https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads

#### ha kell a CUDA (opcionalis)
cuda telepites
https://developer.nvidia.com/cuda-downloads
2.8 GByte

szukseges szabad lemezterut 1.22 GByte
### windows
```shell
python -m venv tf
```
Ativáljuk az új virtuális környezetet!
```shell
tf\Scripts\activate
```

Telepítsük fel a függőségeket!
```shell
pip install -r requirements.txt
```

### linux
```shell
python3 -m venv tf
```

Ativáljuk az új irtuális környezetet!
```shell
source tf/bin/activate
```

Telepítsük fel a függőségeket!
```shell
pip install -r requirements.txt
```
