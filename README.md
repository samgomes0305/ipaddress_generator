# ipaddress_generator

## Descrição
Este script Python utiliza a biblioteca `ipaddress` para gerar e imprimir uma lista de endereços IP pertencentes à rede especificada. O endereço IP inicial e a máscara de sub-rede são definidos na variável `ip`, e a biblioteca `ipaddress` é utilizada para criar uma rede IP com base nesses parâmetros.

## Funcionalidades
- Gera e imprime uma lista de endereços IP pertencentes à rede especificada.
- Utiliza a biblioteca `ipaddress` para manipulação de endereços IP.

## Requisitos
Certifique-se de ter o Python instalado em seu ambiente para executar o script. Não é necessário instalar bibliotecas adicionais, pois a `ipaddress` faz parte da biblioteca padrão do Python 3.

## Como Executar
1. Abra um terminal no diretório onde o arquivo `ipaddress_generator.py` está localizado.
2. Execute o comando:

    ```bash
    python ipaddress_generator.py
    ```

## Resultado Esperado
O script imprimirá na tela todos os endereços IP pertencentes à rede especificada, começando pelo endereço inicial.

Exemplo de saída:
```
192.168.0.0
192.168.0.1
192.168.0.2
...
```

## Observações
- A variável `ip` define o endereço inicial e a máscara de sub-rede da rede a ser gerada. Certifique-se de ajustar conforme necessário.
- O argumento `strict=False` na criação da rede permite a criação de uma rede com uma máscara de sub-rede não estritamente válida. Isso é útil para gerar endereços IP em toda a faixa especificada.

**Nota:** Este script é um exemplo simples para fins educativos. Certifique-se de compreender os conceitos de endereçamento IP e redes ao usar em contextos mais complexos.
