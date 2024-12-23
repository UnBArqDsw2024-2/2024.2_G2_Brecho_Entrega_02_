# 2.1.1 - Diagrama de Classe

## Introdução

Segundo Serrano (2024), diagrama de classe é um diagrama UML que reúne classes (com seus atributos e métodos),interfaces e relacionamentos, como agregações e composições.

## Metodologia

A criação de um diagrama de classes segue etapas estruturadas que garantem a precisão e clareza do modelo. Os passos são listados a seguir.

### Identificação das Classes

O primeiro passo para a elaboração do diagrama é identificar quais são os elementos que compõem o sistema, definindo assim as classes.

### Definição de Atributos e Métodos

Após definir as classes, deve-se pensar nos atributos que as caracterizam e quais funcionalidades possuem (métodos), bem como a visibilidade de cada um (public, protected, private).

### Determinar Relacionamentos

Uma vez que as classes estão devidamente descritas, deve-se verificar se existe relacionamento entre elas (como agregação e composição), assim como a cardinalidade.

### Modelagem Visual do Diagrama

Por fim, o último passo é realizar a modelagem visual do diagrama, usando uma ferramenta adequada para modelagem UML. Para esse diagrama, foi utilizao o LucidChart.

## Diagrama

Foi elaborado o diagrama de classe do UnBrechó, resultando na definição de cinco classes: Product, Order, ShoppingCart, User e Admin, e seus respectivos relacionamentos.

<br><figcaption align="center">Figura 1 - Diagrama de Classes.</figcaption>

![Diagrama de Classes](../Imagens/diagrama_classe.png)

<figcaption align="center">Fonte: <a href="https://github.com/LucasSpinosa" target="_blank">Lucas Spinosa</a>, <a href="https://github.com/MarcoTulioSoares" target="_blank">Marco Tulio</a>,<a href="https://github.com/M4RINH0" target="_blank"> Douglas Marinho</a>, 2024.
</figcaption><br>

Conforme é possível ver, existem os seguintes relacionamentos entre elas:

- Admin possui herança com User;
- User possui agregação com Product e Order;
- User possui associação com Shopping Cart;
- ShoppingCart possui agregação com Product;
- Order possui agregação com Product;
- Order possui dependência com ShoppingCart, visto que precisa da classe para executar uma função (placeOrder).

# Referência Bibliográfica

> SERRANO, Milene. Arquitetura e Desenho de Software: AULA - MODELAGEM UML ESTÁTICA. Disponível em: <https://aprender3.unb.br/pluginfile.php/2928947/mod_page/content/1/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Est%C3%A1tica%20-%20Profa.%20Milene.pdf>. Acesso em: 23 out. de 2024.

# Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) | Resultado da Revisão |
| ------ | ---- | --------- | --------- | ----------- | -------------------- |
| `1.0` | 25/11/2024 | Adição do Diagrama de Classe | [LucasSpinosa](https://github.com/LucasSpinosa), [Marco Tulio](https://github.com/MarcoTulioSoares), [Douglas Marinho](https://github.com/M4RINH0) e [Luiz Pettengill](https://github.com/LuizPettengill) | [Ana Hoffmann](https://github.com/AnHoff) | Melhorar o texto de Metodologia |
| `1.1`  | 26/11/2024 | Reescrita da Metodologia | [LucasSpinosa](https://github.com/LucasSpinosa) | [Ana Hoffmann](https://github.com/AnHoff) | Aprovar PR |