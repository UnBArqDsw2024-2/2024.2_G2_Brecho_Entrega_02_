# 2.2.3 Diagrama de Sequência

## Introdução

Os diagramas de sequência são uma parte essencial da modelagem UML (Unified Modeling Language), representando a interação entre os objetos de um sistema ao longo do tempo. Ele representa os objetos envolvidos no processo e as mensagens trocadas entre eles, facilitando a compreensão do comportamento dinâmico do sistema.

## Metodologia

A construção do diagrama foi realizada com a ferramenta LucidChart e de forma assíncrona, de modo que cada envolvido em seu desenvolvimento contribuiu de modo individual. Ao final, as contribuições foram analisadas e unidas, a fim de criar a versão final do diagrama.

A metodologia utilizada para a criação de um diagrama de sequência envolve as etapas a seguir:

### Identificação do Escopo

Determinar o cenário ou funcionalidade que o diagrama deve representar e especificar os objetivos e as interações principais, como fluxos de login ou processamento de dados.

### Identificação de Elementos e Objetos

Listar os atores e objetos envolvidos no cenário. Além disso, para cada objeto, deve ser definido seu papel no processo e suas interações com outros elementos.

### Definição da Linha do Tempo

Estabelecer a sequência temporal das ações e organizar os eventos em ordem cronológica para que a lógica do processo fique clara.

### Modelagem das Mensagens e Chamadas

Representar cada interação entre os objetos e atores por setas (mensagens).

Usar mensagens síncronas e assíncronas, conforme necessário:

- Síncronas: quando o emissor aguarda uma resposta antes de continuar.
- Assíncronas: quando o emissor continua seu processo sem aguardar uma resposta imediata.

### Representação Visual no Diagrama

Utilização uma ferramenta de modelagem UML (LucidChart) para construir o diagrama.

Os elementos principais incluem:

- Objetos/Atores: representados como retângulos com linhas de vida verticais;
- Mensagens: setas horizontais indicando a troca de informações;
- Respostas: setas pontilhadas representando retornos ou confirmações.

### Validação e Refinamento

Compartilhar o diagrama com as partes interessadas para revisão e verificar se a sequência está lógica e completa. Realizar ajustes conforme necessário.

### Documentação e Uso Futuro

Anexar o diagrama à documentação do projeto e utilizá-lo como referência para o design do sistema, testes ou comunicação entre equipes.

## Diagrama

O diagrama de sequência elaborado pode ser conferido no Diagrama 1 abaixo. Devido ao tamanho do diagrama, optou-se por representá-lo de forma interativa para melhorar a visualização.

<br><figcaption align="center">Diagrama 1 - Diagrama de Sequência</figcaption>

<div style="width: 100%; height: 780px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/ee41648b-4ed6-4303-bbb1-680bb1bd190c" id="UBvvva.Xz.KA"></iframe></div>
<br><br>

<figcaption align="center">Fonte: <a href="https://github.com/eduard0803" target="_blank">Eduardo Belarmino</a> e <a href="https://github.com/AnHoff" target="_blank">Ana Hoffmann</a>, 2024.
</figcaption><br>

## Referências Bibliográficas 

> IBM Diagramas de Seqüência, 2024. Disponível em: [IBM Rational Software Modeler](https://www.ibm.com/docs/pt-br/rsm/7.5.0?topic=uml-sequence-diagrams). Acesso em: 26 nov. de 2024.

> SERRANO, Milene. Arquitetura e Desenho de Software: AULA - MODELAGEM UML ESTÁTICA. Disponível em: <https://aprender3.unb.br/pluginfile.php/2928947/mod_page/content/1/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Est%C3%A1tica%20-%20Profa.%20Milene.pdf>. Acesso em: 26 nov. de 2024.

## Histórico de Versões

| Versão | Data       | Descrição              | Autor(es)                                                                                                                                          | Revisor(es)                                          | Resultado da Revisão                                         |
| ------ | ---------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| `1.0`  | 27/11/2024 | Adição do Diagrama de Sequência | [Eduardo Belarmino](https://github.com/eduard0803) e [Ana Hoffmann](https://github.com/AnHoff) | --- | --- |