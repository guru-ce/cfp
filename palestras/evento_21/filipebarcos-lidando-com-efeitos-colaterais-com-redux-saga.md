# Lidando com Efeitos Colaterais com Redux Saga

## Introdução

Redux é praticamente um padrão em aplicações React por aí, entretanto, Redux por si só não te ajuda a lidar com efeitos colaterais da sua aplicações. Como fazemos isso de forma testável e desacoplada?

## Descrição

Redux Saga definine __Efeitos Colaterais__ como tudo aquilo que você pode considerar uma integração com agentes externos a sua aplicação, como APIs externas, __localStorage__ e outros mais.

O Redux por si só não te ajuda com isso, já que o __reducers__ devem ser funções puras que recebem o estado atual da aplicação e gera um novo, tornando-o o estado atual.

A idéia da palestra é mostrar como o Redux Saga pode nos ajudar a lidar de forma mais organizada, desacoplada e testável com esses efeitos colaterais.

## Palestrante
- Nome: Filipe Costa
- Twitter: @filipebarcos
- GitHub: @filipebarcos

### Bio

Com 8 anos de experiência como desenvolvedor, já liderous times de full stack, backend e agora, mais recente, lidera um time de frontend, usando React e tecnologias relacionadas. Amante de café e cerveja.
