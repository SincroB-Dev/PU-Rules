# Regras de Organização de Projeto na Trello

Para um projeto mais organizado, e para evitar-mos confusões durante o desenvolvimento e também acelerar nosso processo sem atrabalhar os integrantes da equipe, peço encarecidamente que **TODOS** leiam e sigam os procedimentos para utilizar a plataforma **Trello**.

Este documento está aberto para que todos possam ajudar a melhorar nossa organização, a fim de termos uma melhor performance em nosso trabalho.

## Cards

Os Cards devem estar sempre orgânizados, seguem as regras para estes:

- Títulos **NÃO** devem possuir mais que **50 caracteres**, e devem especificar bem **onde** o problema ou tarefa se encontra.
  - Não sobrecarregue títulos, caso queira explicar mais sobre o problema, detalhe na descrição.
  - Não relatar mais de 1 problema na descrição, caso tenha mais problemas, adicione um **Check-List**.
- **SEMPRE** marcar o **Card** com as devidas etiquetas, no caso existem 6:
  - **Hands On** significa que está em trabalho, só deve aparecer quando estiver **Em Execução**.
  - **Impacto Leve** deve aparecer para deixar desenvolvedores menos preocupados com a correção, tudo que seja de importância mínima.
  - **Impacto Médio** deve aparecer em **Cards** com importância média, por exemplo: Cores de tela, textos errados, bugs visuais.
  - **Crítico** deve aparecer em **Cards** com problemas sérios, por exemplo: Telas que apresentam problemas, exposição de erros do server, itens com bugs que atrapalham o funcionamento correto da tarefa.
    - **SEMPRE** marcar uma data limite em cards críticos.
  - **Pausado** somente deve aparecer **Em Execução**.
    - Quando o item estiver **Pausado**, significa que responsável pelo problema o pausou por um tempo indeterminado.
    - Cards críticos não podem receber este estado.
    - Deve-se comentar o motivo da pausa do **Card** em execução.
  - **Aguardando Informações** este **Card** deve chamar a atenção do @author do mesmo, sempre que alguém colocar um **Card**, e ver esta etiqueta, deve abrir e ler os comentários.
- Utilizar **Marcação de Membros**, não digitar o nome do membro a efetuar a execução, marcar o mesmo com a ferramenta.

## Listagens

Onde os cards vão estar deve receber atenção total de analistas e desenvolvedores.

- **Backlog**

  - Novos Cards devem sempre entrar em **Backlog** quando forem:
    - Alguma correção de código.
    - Analise de algum item visual em **Site/App**.
    - Discussão de regras de negócio.
    - Melhorias em **Site/App**.
  - Cards não devem passar mais que, **3 semanas/15 dias**, no **Backlog** sem revisão, ou cobrança pelo @author.

- **Em Execução**

  - Novos Cards não devem ser criados em execução.
  - Não pode ter mais que **2 cards** por um único **Desenvolvedor/Analista**.
    - Não pegue muitas tarefas para fazer, conclua as que está executando e depois que concluir pegue uma nova.
  - Ao concluir sua tarefa, jogue este **Card** em **Concluído** e **AVISE** no grupo, se possível marcar com **@** o @author do Card.

- **Para Testar**

  - Novos Cards devem entrar em **Para Testar** sempre que forem referentes a testes.
  - Ao concluir o card, jogue este **Card** em **Concluído** e **AVISE** no grupo, se possível marcar com **@** o @author do Card.

- **Revisão de Código**

  - Funciona exatamente como **Em Execução**, porém, só entra tarefas referentes a correção de bugs.

- **Concluído**
  - Cards que foram concluídos, devem ser arquivados após **1 semana** da conclusão, somente podem ser arquivados pelo @autor, e somente após a revisão.
