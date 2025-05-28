# Requisitos Iniciais - UniHub

## Visão Geral

**UniHub** é uma plataforma colaborativa criada para facilitar a troca de informações entre estudantes sobre as disciplinas ofertadas no Centro de Informática da UFPE. O objetivo é reunir percepções práticas sobre as matérias — como carga de trabalho, didática dos professores, desafios comuns e dicas úteis — para apoiar os alunos no processo de matrícula, promovendo escolhas mais alinhadas aos seus perfis e objetivos acadêmicos.

---

## Requisitos Funcionais (RF)

| Código | Requisito Funcional | Descrição |
|--------|---------------------|-----------|
| RF01 | Cadastro e login de usuários | Permitir que alunos se cadastrem e façam login para acessar e publicar conteúdo. |
| RF02 | Postagem de experiências | Usuários logados devem poder publicar relatos e dicas sobre disciplinas já cursadas. |
| RF03 | Listagem e busca de disciplinas | A plataforma deve permitir buscar e filtrar disciplinas por nome, código ou professor. |
| RF04 | Edição e exclusão de postagens | Usuários podem editar ou remover seus próprios relatos. |
| RF05 | Reações ou comentários | É possível reagir (curtir, útil, etc.) ou comentar nos relatos de outros usuários. |
| RF06 | Exibição de anúncios | A plataforma deve suportar a exibição de anúncios para viabilizar sua sustentabilidade. |

---

## Requisitos Não Funcionais (RNF)

| Código | Requisito Não Funcional | Descrição |
|--------|--------------------------|-----------|
| RNF01 | Interface responsiva | A aplicação deve ser acessível e funcional em diferentes dispositivos (desktop, tablet, mobile). |
| RNF02 | Desempenho | O tempo de carregamento da interface não deve ultrapassar 2 segundos em redes 4G. |
| RNF03 | Segurança | A autenticação e os dados dos usuários devem ser protegidos (uso de JWT, HTTPS, etc.). |
| RNF04 | Escalabilidade | A aplicação deve suportar ao menos 1.000 usuários simultâneos sem perda de performance. |
| RNF05 | Padrão de APIs | O backend deve seguir o padrão RESTful para suas rotas. |

---

## 👤 Persona

**Nome:** Joyce  
**Idade:** 27 anos  
**Curso:** Ciência da Computação — UFPE  
**Necessidade:** Planejar melhor sua matrícula, buscando relatos de colegas sobre disciplinas antes de escolhê-las.  

---

## 🧾 Histórias de Usuário

> Formato: _Como [persona], quero [algo] para [benefício]._

**HU01.**  
Como **Joyce**,  
quero buscar experiências de outros alunos sobre disciplinas específicas,  
para tomar decisões mais seguras na hora da matrícula.

**HU02.**  
Como **aluna**,  
quero compartilhar minha experiência com uma disciplina que já cursei,  
para ajudar outras pessoas a entenderem melhor a matéria.

**HU03.**  
Como **usuária logada**,  
quero editar ou apagar um relato que escrevi,  
para manter minhas informações atualizadas.

**HU04.**  
Como **usuária**,  
quero ver quais disciplinas têm mais relatos ou curtidas,  
para descobrir quais matérias geram mais discussão ou dúvidas.

---

## 📌 Observações Finais

Este documento descreve os requisitos iniciais do projeto e será expandido conforme a evolução do desenvolvimento. Versões futuras podem incluir:

- Sistema de tags por tipo de disciplina (teórica, prática, optativa, obrigatória)
- Filtros por semestre, professor e dificuldade
- Notificações personalizadas e rankings por feedback

---

