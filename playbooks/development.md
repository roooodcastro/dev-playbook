# Playbook de Desenvolvimento.

(Esse playbook foi criado com as nossas práticas do dia-a-dia e com ajuda inspiracional do [playbook da thoughtbot(em inglês)](https://playbook.thoughtbot.com/#developing).

Acreditamos fortemente em [Extreme Programming](https://en.wikipedia.org/wiki/Extreme_programming), trabalhando com sprints de 15 dias para entregas de requisitos. Isso nos ajuda a trabalhar melhor, mantendo a qualidade do sistema e deixando nossos desenvolvedores felizes. :) 
Para as nossas práticas, nomes como Kent Beck, Martin Fowler, Bob Martin e Sandi Metz são muito importantes para nós.

## Controle de Versão

Trabalhamos com [Git](http://git-scm.com/) para controle de versão, pois adoramos a facilidade de branching e merging que ele nos dá. Temos o nosso [repositório público no github](https://github.com/sti-uff), onde está atualmente esse guia, e o nosso repositório privado para desenvolvimento, o [Gitlab](https://about.gitlab.com/). Ainda não utilizamos tudo o que o Gitlab nos permite, mas estamos trabalhando nisso! Caso você ainda não tenha acesso ao [nosso repositório de gitlab](https://sistemas.uff.br/sti/git/), informe o seu mentor/gerente.

Trabalhamos com 3 branches principais, a 'master' para desenvolvimento, 'homologacao' para homologarmos o sistema com o cliente e a branch de 'producao'. A princípio você trabalhará na master, podendo criar suas próprias branches conforme a tarefa demandar. Em breve pretendemos começar a trabalhar com pull requests, então possívelmente revisaremos as nossas branches. Os merges para homologação e produção costumam ser feitos pelo líder técnico da equipe, responsável por revisar o seu código. Note que uma revisão de código NÃO É para censurar o desenvolvedor, e sim auxiliá-lo em sua evolução pessoal, tal como melhorar a qualidade do sistema. :)