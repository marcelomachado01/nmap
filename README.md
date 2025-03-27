# Scanner de Portas Simples com Python 🐍

Este script Python realiza um escaneamento básico de portas em um endereço IP alvo. Ele verifica se portas comuns estão abertas e exibe os resultados no terminal.

## Funcionalidades

* **Entrada do Endereço Alvo :**
    * Solicita ao usuário que digite o endereço IP do alvo que deseja escanear.
    * Utiliza a função `input()` para obter a entrada do usuário.
* **Escaneamento de Portas Comuns :**
    * Verifica se as seguintes portas estão abertas: 21, 22, 23, 25, 28, 443, 80 e 8080.
    * Utiliza a biblioteca `socket` para criar conexões TCP com o alvo.
    * Define um tempo limite de 0.7 segundos para cada conexão.
* **Exibição de Portas Abertas :**
    * Exibe as portas que estão abertas no terminal, juntamente com o status "OPEN".
    * Utiliza códigos de cores para destacar as portas abertas.
* **Indicação de Finalização :**
    * Exibe uma mensagem indicando que o escaneamento foi concluído.
    * Adiciona um pequeno delay para melhorar a experiência do usuário.

## Como Usar

1.  **Instale o Python :**
    * Certifique-se de que o Python esteja instalado no seu sistema.
2.  **Salve o script :**
    * Copie o código do script e salve-o em um arquivo com a extensão `.py` (por exemplo, `scanner.py`).
3.  **Execute o script :**
    * Abra o terminal e navegue até o diretório onde você salvou o script.
    * Execute o script com o comando `python scanner.py`.
4.  **Digite o endereço alvo :**
    * Quando solicitado, digite o endereço IP do alvo que deseja escanear e pressione Enter.
5.  **Visualize os resultados :**
    * O script exibirá as portas abertas no terminal.

## Requisitos

* Python 3
* Biblioteca `socket` (geralmente incluída na instalação padrão do Python)
* Biblioteca `time` (geralmente incluída na instalação padrão do Python)

## Contribuição

* Contribuições são bem-vindas!
* Sinta-se à vontade para abrir issues e pull requests para melhorias e novas funcionalidades.
* Compartilhe suas ideias!
