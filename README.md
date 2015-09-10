# Boas Práticas de Desenvolvimento
Lista de Boas Práticas do desenvolvedor moderno.

##Fluxo de desenvolvimento
1. Crie um novo branch no seu repositório local.
2. Implemente suas mudanças
3. Faça um push do seu branch para o repositório remoto
4. Submeta um Pull Request (no caso do GitHub, na página do repositório ou utilizando a aplicação desktop)
5. Aguarde a revisão do mesmo por outros desenvolvedores da sua equipe
6. Caso alguma mudança seja solicitada, implemente-a.
7. Seus colegas de equipe integrarão seu código quando ele estiver ok.

A etapa 6 é feita na página de discussão do pull request. Nela é possível fazer comentários sobre trechos de código ou sobre o pull request em geral, tal como um fórum.

Exemplo: https://github.com/coopera/teamtracker/pull/44

Orientações:
- Revisor:
  - Seja cordial com quem está submetendo o pull request. 
  - Assuma que ele não necessariamente possui o mesmo conhecimento que você e seja claro com seus pedidos de mudança.
  - Caso conheça algum tutorial ou link útil para resolver algum problema apontado, compartilhe-o na área de discussão do pull request.
- Desenvolvedor que submeteu o pull request:
  - Responda os questionamentos dos revisores.
  - Caso algum revisor tenha solicitado algo e você não consiga entender a solicitação, não hesite em questioná-lo.

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
