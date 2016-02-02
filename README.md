# CFP do Guru CE

## Motivação

A intenção desse repositório é centralizar e deixar aberto para qualquer usuário do github poder votar nas palestras do Guru CE e também manter um registro centralizado de propostas.

## Como saber de novos Encontros

Os encontros são sempre divulgados no [site do Guru](http://guru-ce.github.io), no [grupo do facebook](https://www.facebook.com/groups/guruce/), na [lista de discussões](https://groups.google.com/forum/#!forum/guru-ce) e no [slack](https://guru-ce-slack.herokuapp.com/), se você ainda não faz parte, aproveita e se inscreve pra ficar sabendo de tudo. Além disso, agora novas issues serão adicionadas neste repositório.

## Como submeter palestras

Para cada encontro, será criado um novo diretório dentro da pasta de `palestras`, com a data do evento. Os pull requests devem seguir o modelo presente em `palestras/modelo.md`.

1. Abrir um Pull Request referenciando a issue do encontro no título, como `[issue#123]`, onde `123` é o número da issue
2. Adicionar o label `lightning` ou `long` ao seu PR
3. Seguir o modelo fielmente
4. O nome do arquivo deve seguir o padrão `<github-username>-<titulo-da-sua-palestra>.md`. Usar `-` como separador de palavras
5. PR abertos fora do padrão serão notificados, e o usuário que o abriu terá um total de 7 dias para corrigir, caso contrário, o PR será fechado e desconsiderado
6. Caso um proponente submeta uma palestrar para um encontro, e não for selecionada, e desejar submeter a mesma para um outro encontro, deverá ser aberto um novo PR
7. As palestras aceitas serão mergeadas no repositório

