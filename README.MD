### Desafio Cientista de Dados Indicium.

Desafio proposto pela Indicium para o programa Lighthouse. O objetivo do desafio está na identificação de máquinas que apresentam potencial de falha, tendo como base de dados, informações de sensores durante o processo de manufaura, mais informações sobre os dados podem ser encontradas através do seu dionário neste [link](https://github.com/Lineker98/desafio-indicium/blob/main/%5BLighthouse%5D%20Desafio%20Cientista%20de%20Dados%20-%20Manuten%C3%A7%C3%A3o%20preventiva.docx). O problema é caracterizado com *multiclass classification*, além disso, alguns desafios foi lidar o desbalanceamento das classes, tratadas no [notebook](https://github.com/Lineker98/desafio-indicium/blob/main/modeling.ipynb) de modelagem.

#### Instruções para execução do código.

Para execução com projeto, é necessário que sua máquina tenha instalado o python e seu gerenciador de pacotes, o pip. Assim podemos seguir os segintes passos:

- Baixe o repositório em sua máquina, ou clone no terminal com o comando:

```
git clone https://github.com/Lineker98/desafio-indicium.git
```

- Criação do ambiente virtual para instalação das dependências:
```
pip install virtualenv
```

- Com o venv instalado, e dentro do diretório do projeto, execute:
```
python3 -m venv <nome_do_ambiente>
```

- Para ativação do ambiente, digite no terminal
    - Linux:
    ```console
    source <nome_do_ambiente>/bin/activate
    ```

    - Windows:
    ```
    <name_of_environment>\Scripts\activate
    ```

- Com o ambiente já instalado e ativado, precisamos agora instalar as dependências, ainda no terminal, digite:
```
pip install -r requirements.txt
    ```

Pronto! Você já está apto a executar todo projeto e verificar os resultados!