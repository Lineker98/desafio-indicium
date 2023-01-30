### Desafio Cientista de Dados Indicium.

Desafio proposto pela Indicium para o programa Lighthouse. O objetivo do desafio está na identificação de máquinas que apresentam potencial de falha, tendo como base de dados, informações de sensores durante o processo de manufaura, mais informações sobre os dados podem ser encontradas através do seu dionário neste [link](). O problema é caracterizado com *multiclass classification*, além disso, alguns desafios foi lidar o desbalanceamento das classes, tratadas no [notebook]() de modelagem.

#### Instruções para execução do código.

Para execução com projeto, é necessário que sua máquina tenha instalado o python e seu gerenciador de pacotes, o pip. Assim podemos seguir os segintes passos:

    - Baixe o repositório em sua máquina, ou clone no terminal com o comando:

    ```
    git clone ...
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
        ```
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