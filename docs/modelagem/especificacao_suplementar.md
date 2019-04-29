## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|   29/04/2019   | Gabriel Filipe Manso Araujo  | Criação da página | 0.0  |

#Documento de Especificação Suplementar

Este documento tem por finalidade a descrição mais elaborada de requisitos não funcionais encontrados ao longo da elaboração da documentação de análise de requisitos da aplicação MEDIUM.


#Finalidade e Escopo
O objetivo do documento é cobrir os todos os requisitos não funcionais levantados nessa documentação até o dia 29 de Abril de 2019.

#Visão Geral
Os requisitos estão aqui separados por Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Sistemas de Ajuda, Segurança e Protabilidade.

Embora sejam anexados pelas categorias descritas acima, mantém-se as indexações padronizadas pela wiki, tornando mais fácil a visualização dele ao longo da documentação.

#Referências

A formatação deste documento foi baseada no template da Fundação da Universidade Federal do Paraná e do grupo da matéria de Requisitos de Software da Universida de Brasília de 2018, com o tema a aplicação Trello. Algumas alterações foram feitas para melhor adequação à realidade na qual as especificações aqui descritas se enquadram.

***

#Portabilidade

O MEDIUM é uma aplicação que está disponível em vários tipos de sistemas operacionais (S.O). Sendo encontrada, por exemplo, em versão web, aplicativo Android ou iOS

*** 

#Funcionalidades
Acredita-se que todos os requisitos funcionais estão suficientemente modelados através de histórias de usuário descritas na [Baseline](../baseline.md).

*** 

#Usabilidade
Através dos Casos de Uso foi possível modelar alguns dos requisitos que o sistema teria de atender para que esse importante critério pudesse ser considerado atendido pela equipe.

Aqui serão descritas as operacionalizações identificadas nos Casos de Uso, pois esse é o nível do diagrama que reflete a implementação pelos desenvolvedores do sistema.

## Responsividade com Tamanho de Tela
Para atender de maneira dinâmica a variedade de tamanhos de tela que se encontram hoje no mercado, é necessário que a estrutura CSS das telas seja construída de maneira a responder uniformemente a cada configuração dimensional.

## Detecção de Idioma
No contexto do app a aplicação possuí a troca de idioma automático para o idioma padrão do dispositivo, possibilitando uma maior inclusão de usuários. Já no website temos a insuficiência deste recurso.

***