# WebAPI

## Install

### Stwórz prywatny klucz dostępu

* Wejdź na stronę: https://github.com/settings/tokens/new`
* Podaj dane do logowania. 
* Na kolejnej zaznacz jedynie: **public_repo Access public repositories**
* Skopiuj klucz, typu: **abc_lskdllkA8784k4jrkjkj9s9d89090dafisdi**

Gotowe repo:

```shell
git clone ...
cd ...

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

```shell
mkdir github
cd github
python3 -m venv venv
source venv/bin/activate
pip install ipython
pip install PyGithub
pip install jupyterlab
```