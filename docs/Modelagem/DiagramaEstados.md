# 2.2.2 - Diagrama de Estados

## Introdução

De acordo com os princípios da modelagem UML, um diagrama de estados é utilizado para representar o ciclo de vida de um objeto, destacando os estados que ele pode assumir e as transições entre esses estados. Este diagrama é fundamental para entender como o carrinho de compras do sistema de brechó UnBrechó responde às interações do usuário e aos eventos do sistema.

## Metodologia

A criação do diagrama de estados seguiu uma abordagem sistemática para garantir que todos os possíveis estados do carrinho fossem representados e todas as transições relevantes fossem mapeadas.

### Identificação dos Estados

Foram identificados os seguintes estados principais no ciclo de vida do carrinho:

1. Carrinho Vazio: Representa o estado inicial, onde nenhum item foi adicionado.
2. Adicionar Item: O estado transitório enquanto o usuário inclui itens no carrinho.
3. Remover Item: Representa a remoção de itens existentes no carrinho.
4. Pagamento: Estado onde o usuário finaliza a compra e insere os dados de pagamento.
5. Finalizado: O carrinho é concluído e o pedido é gerado.
6. Desistência: Estado em que o usuário cancela a compra, esvaziando o carrinho.

### Definição de Eventos e Transições

Cada estado é conectado por transições disparadas por eventos do usuário ou do sistema:

- Adicionar Item: Transição de "Carrinho Vazio" para "Adicionar Item".
- Remover Item: Transição de "Adicionar Item" ou "Pagamento" para "Remover Item".
- Finalizar: Transição de "Adicionar Item" para "Pagamento".
- Fechar Compra: Transição de "Pagamento" para "Finalizado".
- Desistir da Compra: Transição de qualquer estado para "Carrinho Vazio".

### Modelagem Visual do Diagrama

O diagrama foi modelado utilizando a ferramenta LucidChart, resultando em um fluxo claro e organizado que reflete o ciclo de vida do carrinho de compras.

---

## Diagrama

O diagrama dinâmico de estados apresenta os seguintes elementos:

1. Estado Inicial: Representado pelo símbolo de círculo preenchido.
2. Estados Finais: Representados por um círculo com borda dupla.
3. Transições: Mostram como o sistema responde a eventos como "Incluir", "Retirar" e "Finalizar".
4. Estados Intermediários: Como "Adicionar Item" e "Remover Item", que indicam ações em andamento.

---

<br><figcaption align="center">Figura 2 - Diagrama de Estados do carrinho de compras.</figcaption>

![Diagrama de estados do carrinho de compras](../Imagens/diagrama_estado_carrinho.png)

<figcaption align="center">Fonte: <a href="https://github.com/Ericcs10" target="_blank">Eric Camargo</a>, <a href="https://github.com/M4RINH0" target="_blank">Douglas Marinho</a> e <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>, 2024.
</figcaption><br>

## Conclusão

O diagrama de estados do carrinho de compras permite visualizar como o sistema responde às interações do usuário e assegura a correta implementação do ciclo de vida do carrinho. Essa modelagem auxilia no desenvolvimento, testes e documentação do sistema, garantindo uma experiência de usuário fluida e eficiente.

## Referências Bibliográficas 

> SERRANO, Milene. Arquitetura e Desenho de Software: AULA - MODELAGEM UML ESTÁTICA. Disponível em: <https://aprender3.unb.br/pluginfile.php/2928947/mod_page/content/1/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Est%C3%A1tica%20-%20Profa.%20Milene.pdf>. Acesso em: 26 nov. de 2024.

## Histórico de Versões

| Versão | Data       | Descrição              | Autor(es)                                                                                                                                          | Revisor(es)                                          | Resultado da Revisão                                         |
| ------ | ---------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 27/11/2024 | Adição do Diagrama de Estados do carrinho | [Eric Camargo](https://github.com/Ericcs10), [Douglas Marinho](https://github.com/M4RINH0) e [Henrique Torres](https://github.com/henriqtorresl) | [Ana Hoffmann](https://github.com/) | Resolução de conflitos + ajustes de estilo da página |