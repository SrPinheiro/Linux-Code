1 passo - fazer o download do geckodriver do Firefox:

https://github.com/mozilla/geckodriver/releases

2 passo - instalar o geckodriver:

    Descompactar o arquivo gecko
    Mover ele para a sua pasta BIN
    sudo mv geckodriver /usr/local/bin
    sete a PATH
    export PATH=$PATH:/usr/local/bin/geckodriver

3 passo - instale a biblioteca virtual:

    python3 -m venv env
    source env/bin/activate

4 passo - instale o selenium:

    pip install selenium

5 passo - Seja feliz :D
