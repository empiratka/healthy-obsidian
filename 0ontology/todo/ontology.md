Мы **не воспроизводим одну конкретную онтологию из учебника**.  
То, что мы строим, — это **синтез нескольких школ**:
- формальной онтологии (computer science / semantic web),
- научного knowledge representation,
- прикладных онтологий в биомедицине,
- и практик personal knowledge management (PKM, Zettelkasten).
# Базовые принципы онтологии (теория)

## Gruber, 1993
**“A Translation Approach to Portable Ontology Specifications”**
Ключевая фраза (очень важная):
> _An ontology is an explicit specification of a conceptualization._

Отсюда у нас:
- entities
- relations
- constraints
Это _канон_, от которого отталкиваются почти все.
## Guarino, 1998
**“Formal Ontology and Information Systems”**
Здесь появляется:
- различие между
    - объектами
    - состояниями
    - процессами
- идея **онтологической чистоты**

Именно отсюда логика:
- deficiency ≠ vitamin
- absorption ≠ nutrient
# Прикладные онтологии в биомедицине (ключевой слой)
## OBO Foundry
[https://obofoundry.org/](https://obofoundry.org/)

Это **золотой стандарт** биомедицинских онтологий.
Обрати внимание на:
- **BFO (Basic Formal Ontology)**
- **RO (Relations Ontology)**

Там чётко разделены:
- material entity
- process
- role
- disposition
## ChEBI
**Chemical Entities of Biological Interest**

Как они делают:
- entity ≠ role
- entity ≠ biological effect
# Knowledge Graph & Semantic Web (структура связей)

Это слой, откуда у нас:
- interaction как отдельный объект
- длинные “рукопожатия”
- отказ от прямых связей “всё со всем”
## “Knowledge Graphs” — Hogan et al., 2021

Ключевые идеи:
- reification of relations
- n-ary relations
- event-centric modeling
**Interaction = reified relation** — именно отсюда.
# Научное мышление

Мы **осознанно** используем структуру научных обзоров.
## 📘 Systematic Review methodology (PRISMA)

- PRISMA flow diagram
- evidence hierarchy

Отсюда у нас:
- study ≠ conclusion
- evidence ≠ synthesis
- confidence levels
# 5️⃣ PKM и Zettelkasten (адаптация под Obsidian)

## 🧠 Niklas Luhmann — Zettelkasten
- атомарные заметки
- связность
- отсутствие иерархий

Но мы:
- **усилили типизацию**
- добавили оси
- убрали “литературный хаос”