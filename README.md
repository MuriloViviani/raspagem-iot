# Raspagem IoT

Exemplos simples de aplica��es de raspagem de dados utilizando a placa Intel Edison.

## Pr�-requisitos
- [Python 2.7](https://www.python.org/downloads/release/python-2713/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)
- [requests](https://github.com/requests/requests)
- [upm](https://github.com/intel-iot-devkit/upm/blob/master/docs/installing.md)
- [Kit Intel Edison para Arduino](https://www.intel.com.br/content/www/br/pt/products/boards-kits/edison/kit-for-arduino.html)
- [Grove - Starter Kit Plus Gen 2](https://www.seeedstudio.com/Grove-starter-kit-plus-Intel-IoT-Edition-for-Intel-Galileo-Gen-2-and-Edison-p-1978.html)

## Instala��o

Acesse o Edison

```
# Substitua edison-lmayra pelo nome da sua placa
$ ssh root@edison-lmayra.local
```

Fa�a o clone do projeto e acesse a pasta rec�m-criada

```
# git clone git@github.com:lidimayra/raspagem-iot.git && cd raspagem-iot
```

Execute o exemplo desejado

```
python script.py
```

