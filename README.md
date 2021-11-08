# WebAPI

## Install

### Stwórz prywatny klucz dostępu

* Wejdź na stronę: https://github.com/settings/tokens/new`
* Podaj dane do logowania. 
* Na kolejnej zaznacz jedynie: **public_repo Access public repositories**
* Skopiuj klucz, typu: **abc_lskdllkA8784k4jrkjkj9s9d89090dafisdi**

Jeśli nie macie python3.9 (analogicznie też można 3.10)

    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt update
    sudo apt install python3.9 python3.9-dev python3.9-venv
    sudo apt install python3.10 python3.10-dev python3.10-venv


Instalacja ręczna, sklonuj repo, wejdź do katalogu z projektem i dalej

    python3.9 -m venv venv
    . venv/bin/activate
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver
 
jeżeli nie pójdzie z requirements.txt można zainstalować tylko

    pip install ipython
    pip install PyGithub
    pip install jupyterlab

Potem do powtórki ćwiczenia w plików *.ipynb, możecie je odpalać w pycharmie jako notebooki
albo przeklejać do konsoli pythona. Gdyby ktoś nie wiedział jak to robić niech pisze.

Do tego prośba o import pliku *Insomnia_2021-11-03.json* do programu Insomnia.
Potestowanie zapisanych requestów i dodanie choć jednego swojego do dowolnej strony.
Można uruchomić 2 projekt ze szkolenia i z niego dodać np.: http://127.0.0.1:8000/words/test_get_post
wywołać obiema metodami GET i POST, zobaczyć efekt, nagłówki itp.