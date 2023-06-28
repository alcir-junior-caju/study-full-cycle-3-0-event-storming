# Curso Full Cycle 3.0 - Módulo Event Storming

<div>
    <img alt="Criado por Alcir Junior [Caju]" src="https://img.shields.io/badge/criado%20por-Alcir Junior [Caju]-%23f08700">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23f08700">
</div>

---

## Descrição

O Curso Full Cycle é uma formação completa para fazer com que pessoas desenvolvedoras sejam capazes de trabalhar em projetos expressivos sendo capazes de desenvolver aplicações de grande porte utilizando de boas práticas de desenvolvimento.

---

## Repositório Pai
https://github.com/alcir-junior-caju/study-full-cycle-3-0

---

## Visualizar o projeto na IDE:

Para quem quiser visualizar o projeto na IDE clique no teclado a tecla `ponto`, esse recurso do GitHub é bem bacana

---
### O que é Event Storming
- É uma técnica criada por Alberto Brandolini para que possamos entender de forma mais clara o domínio das aplicações através dos eventos gerados por elas.
- Normalmente acontece em um formato de workshop. É uma dinâmica de grupo envolvendo `domain experts` e a área técnica;

#### Mapeamento dos eventos
- Todo Domain Event é um postiti laranja;
- São eventos relevantes;
- E todos eventos acontece no passado, ex.: productCreated, productAdded, etc;

#### Mapeamento dos eventos - Eventos de finalização de fase
- Ter um postiti maior;

#### Mapeamento dos eventos - Comando
- Todo evento é realizado através de um comando - Postiti Azul;
- A partir de um usuário (Persona) - Postiti Amarelo;

#### Mapeamento dos eventos - Dados para Tomada de decisão
- Postiti verde;

#### Mapeamento dos eventos - Policy `Quando algo acontecer, faça`
- Postiti roxo;

#### Mapeamento dos eventos - Cronologia
- Existem processos que acontecem um após o outros;
- Existem processos que acontecem em paralelo;
- Existem processos que acontecem em áreas diferentes;
- Existe uma ordem para que os pecessos acontecam;

#### Mapeamento dos eventos - Origem dos eventos
- Através de uma ação / comando de um cliente;
- Através de um sistema externo;
- Através do tempo;
- Através de uma Policy;

#### Mapeamento dos eventos - Formação de Aggregates
- Sempre entre um Comando e um Domain Event existe um Aggregate;

#### Mapeamento dos eventos - Pivotal events
- Comunicação entre bounded contexts;
- Eventos que passa a barreira dos contextos;
- Conflitos de ideias HOTSPOT - Postiti rosa;
- Pontos de oportunidades - Postiti Verde claro;

#### Mapeamento dos eventos - Arrow voting
- Você tem um problema Hotspot, ou uma oportunidade, então temos Postitis azuis com setas apontadas para eles, então a tomada de decisão é por votos;

#### Mapeamento dos eventos - Flow
- https://baasie.com/2020/07/16/eventstorming-core-concepts-glossary-and-legend/

#### Link do Event Storming CodeFlix
- https://whimsical.com/event-storming-55FFxo9w23jjPzp7keqX8o
