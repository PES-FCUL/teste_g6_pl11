# PES - Maven

Antes de começares, certifica-te de que:

1. Tens sessão iniciada no GitHub,
2. Tens um Personal Access Token,
3. Configuraste o teu utilizador e email neste computador (podes usar o script `setup.sh`;
   corre-o sem argumentos para ver como se usa).

Neste repositório existe um branch com o teu número de estudante. Nele vais encontrar
um pequeno projeto Maven com duas dependências desatualizadas. Ao fazeres fork, não te
esqueças de fazer fork de **todos** os branches e não apenas do `main`. Caso te esqueças
de fazer fork do teu branch, podes ir buscá-lo fazendo o seguinte:

1. Ir ao teu fork.
2. No selector de branches, escreves o teu número de aluno.
3. O GitHub vai-te perguntar se queres criar um branch com esse nome. Aceita.
4. No novo branch, vai haver um botão a perguntar se queres sincronizar ("Sync") o teu branch
   com o original. Isso vai trazer o branch para o teu fork.

O teu trabalho é:

1. descobrir quais são as dependências desatualizadas,
2. atualizar a versão dessas duas dependências no `pom.xml`,
3. gerar o jar com maven, fazer commit dele e fazer push do teu branch,
4. abrir um PR para o repositório original, com base no teu branch.

Requisitos: JDK 17+, Maven 3.8+, git. Não faças push para o `main` nem para outros branches.

Lê com atenção o README do teu branch: tem uma lista de comandos úteis.

Para mudares para o teu branch:

```
git fetch origin
git checkout <o-teu-numero-de-estudante>
```

Boa sorte!
