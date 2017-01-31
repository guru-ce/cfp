# Sidekiq como Alternativa para Background Jobs

## Introdução

Cedo ou tarde a maioria dos sistemas acabam requerendo o desenvolvimento de scripts mais complexos e que acabam demandando mais tempo de execução. Pode ser um relatório, uma importação de arquivos ou um envio de emails em massa, diversas são as aplicações para os chamados `background Jobs`. Qual seria uma das soluções para esse problema no universo `Ruby on Rails`?

## Descrição

**Sidekiq** juntamente com **Redis** tem sido uma das combinações mais comuns para processos em background.

Nessa palestra pretendo abordar as principais caracteristicas de como funciona, alguns detalhes e dicas de implementação, além de uma comparação básica dentre outras soluções como o próprio `Active Job` e a gem `Delayed::Job`.

Ainda dentro do mesmo contexto, pretendo finalizar mostrando como podemos resolver problemas de recorrência de eventos com a ajuda da gem `clockwork`.

## Palestrante
- Nome: Renan Gurgel
- Twitter: @gurgelrenan
- GitHub: @gurgelrenan

### Bio

Graduado em Ciência da Computação pela UECE, atuou no Movimento Empresa Júnior (MEJ) por 5 anos. Desenvolvedor Backend há 6 anos e atualmente ajuda o crescimento da startup **Agenda Kids**. No mês de junho, se arrisca a dançar Quadrilha :)
