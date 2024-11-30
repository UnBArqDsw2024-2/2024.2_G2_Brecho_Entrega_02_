# 2.2.1 - Diagrama de Comunicação

## Introdução

Segundo Serrano (2024), o diagrama de comunicação é um diagrama dinâmico, ou seja, um diagrama de detalhes comportamentais. Ele mostra a interação entre objetos e/ou partes usando mensagens sequenciais.

É colocada ênfase na ordem das mensagens e, normalmente, o diagrama é feito com foco em um cenário de uso.

## Metodologia

A criação de um diagrama de comunicação segue etapas estruturadas que garantem a precisão e clareza do modelo. Os passos são listados a seguir.

### Determinar o cenário de uso

O primeiro passo é determinar o cenário de uso que será modelado, pois isso indica quais objetos serão necessários na representação.

### Identificar objetos necessários

Com o cenário de uso demarcado, é necessário determinar dentre os objetos do sistema quais são os necessários para que o cenário de uso possa acontecer.

### Modelar Interações

O passo seguinte é modelar as interações entre os objetos, organizando-as em sequência e explicitando quais métodos são usados em cada passo.

### Modelagem Visual do Diagrama

O passo final é usar uma ferramenta de modelagem UML para ilustrar visualmente o diagrama. A criação do mesmo se deu a partir de um trabalho conjunto entre os responsáveis por esse diagrama, com o uso do LucidChart como ferramenta de desenvolvimento.

## Diagrama

Foi elaborado o diagrama de comunicação do UnBrechó tendo em mente o cenário de uso de compra de um produto, que envolve os objetos Cliente, Produto, Carrinho e Order, conforme ilustrado na Figura 1 abaixo.

<br><figcaption align="center">Figura 1 - Diagrama de Comunicação</figcaption>

![Diagrama de comunicacao](../Imagens/diagrama_comunicacao.png)

<figcaption align="center">Fonte: <a href="https://github.com/LucasSpinosa" target="_blank">Lucas Spinosa</a>, <a href="https://github.com/LuizPettengill" target="_blank">Luiz Pettengill</a> e <a href="https://github.com/MarcoTulioSoares" target="_blank">Marco Tulio</a>, 2024.
</figcaption><br>

Conforme apresentado, Cliente interage com Produto usando métodos para obter informações do mesmo. Em seguida, Produto é adicionado ao Carrinho de Compras, que por sua vez informa ao Cliente o valor dos produtos selecionados. Por fim, o Cliente reliza o Pedido e o paga.

## Referências Bibliográficas 

> SERRANO, Milene. Arquitetura e Desenho de Software: AULA - MODELAGEM UML ESTÁTICA. Disponível em: <https://aprender3.unb.br/pluginfile.php/2928947/mod_page/content/1/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Est%C3%A1tica%20-%20Profa.%20Milene.pdf>. Acesso em: 26 nov. de 2024.

## Histórico de Versões

| Versão | Data       | Descrição              | Autor(es)                                                                                                                                          | Revisor(es)                                          | Resultado da Revisão                                         |
| ------ | ---------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 26/11/2024 | Adição do Diagrama de Comunicação | [LucasSpinosa](https://github.com/LucasSpinosa), [Marco Tulio](https://github.com/MarcoTulioSoares) e [Luiz Pettengill](https://github.com/LuizPettengill)  | [Ana Hoffmann](https://github.com/) | Aprovado para merge |