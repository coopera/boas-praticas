# Boas Práticas de Desenvolvimento
Lista de Boas Práticas do desenvolvedor moderno.

##Código
- Escreva no *case* da linguagem.
  - Exemplo: váriaveis e funções em ruby se escrevem em snake_case. Em javascript, em camelCase 
- Escreva no *idioma* da linguagem. Ou seja, a forma mais "natural" de expressar os algoritmos de acordo com a linguagem.
- Código em inglês. Nunca se sabe quem vai ter acesso a ele.

##Controle de versão
- Mensagens de commit devem ser curtas e objetivas. Exemplos:
  - "Fix bug at user controller"
  - "Add sign in feature"
- Commits devem possuir poucas mudanças, em geral. Ou seja: commite constantamente.
- Se o seu código for público, também é preferível que suas mensagens de commit estejam em inglês.
- Caso sua equipe use algum issuetracker (como o do próprio GitHub, por exemplo), lembre-se de referenciar o número da issue em que você está trabalhando no commit. Exemplo:
  - Existe a issue: #10 - Fix password bug.
  - Seu commit que corrige tal bug deve ser algo do tipo: "Change user password algorithm. Fix #10"
