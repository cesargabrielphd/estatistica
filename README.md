# estatistica
[desenvolvimento]-Plataforma de ensino de estatística gratuitamente.

## Padrões de commits 📜

De acordo com a documentação do **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, commits semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

## Tipo e descrição 🦄

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - ndicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` -  são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` -  indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` -referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw` - indicam mudanças relacionadas a arquivos de configurações, dados, features, parametros.

meus novos padrões
- `merge` - indica quando há merges entre branchs

- `acervo` - indicam quando há mudanças no acervo (renomear pastas, mudanças de pastas que estejam dentro do ac)
## 💻 Exemplos
<table>
  <thead>
    <tr>
      <th>Tipo do commit</th>
      <th>Emoji</th>
      <th>Palavra-chave</th>
      <th>exemplo</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td><code>docs</code></td>
    <td>cell2_3</td>
    <td>cell3_3</td>
    <td>cell3_3</td>
  </tr>
  <tr>
    <td><code>build</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
    <tr>
    <td><code>style</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
    <tr>
    <td><code>merge</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>acervo</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>feat</code></td>
    <td>cell2_1</td>
    <td>cell3_1</td>
    <td>cell3_1</td>
  </tr>
  <tr>
    <td><code>fix</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>test</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>perf</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>refactor</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>chore</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>ci</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  <tr>
    <td><code>raw</code></td>
    <td>cell2_2</td>
    <td>cell3_2</td>
    <td>cell3_2</td>
  </tr>
  </tdoby>
</table>


## Padrões de emojis 💈

 - bug :bug: - Correção de bug
 - repeat :repeat: Renomeada a pasta
 - twisted_rightwards_arrows :twisted_rightwards_arrows: merges entre branchs
 - sparkles :sparkles: - Nova funcionalidade
 - wrench :wrench: - Alterações de configuração ou manutenção
 - art :art: - Melhorias de formatação/código
 - fire :fire: - Remoção de código ou arquivos
 - memo :memo: - Atualização de documentação
 - rocket :rocket: - Melhorias de desempenho
 - construction :construction: - Trabalho em andamento (WIP - "Work in Progress")
 - arrow_up :arrow_up: - Atualização de dependências
 - arrow_down :arrow_down: - Redução de dependências
 - recycle :recycle: - Refatoração de código
 - heavy_plus_sign :heavy_plus_sign: - Adição de dependências ou pacotes
 - heavy_minus_sign :heavy_minus_sign: - Remoção de dependências ou pacotes
 - tada :tada: - Um commit inicial, um marco importante ou uma conquista
 - white_check_mark :white_check_mark: - Adição de testes
 - lock :lock: - Melhorias de segurança
 - green_heart :green_heart: - Correções nos testes
 - truck :truck: - Mudanças de movimentação ou renomeação de arquivos
 - package :package: - Mudanças relacionadas a pacotes ou gerenciadores de pacotes
 - bookmark :bookmark: - Versão ou tag