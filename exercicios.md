# Atividades para Fixação do Conteúdo

## Questões de Múltipla Escolha

### Questão 1
Qual palavra-chave em JavaScript NÃO permite a redeclaração de uma variável?
- [ ] `var`
- [ ] `let`
- [x] `const`
- [ ] Todas acima permitem redeclaração

### Questão 2
Em JavaScript, qual tipo de dado é utilizado para representar verdadeiro ou falso?
- [ ] String
- [x] Booleano
- [ ] Número
- [ ] Objeto

### Questão 3
Qual é o escopo de uma variável declarada com `let`?
- [ ] Global
- [x] Bloco
- [ ] Função
- [ ] Nenhuma das anteriores

### Questão 4
Qual dos seguintes é um exemplo válido de declaração de string em JavaScript?
- [ ] `let mensagem = 'Olá, mundo!;`
- [ ] `let mensagem = "Olá, mundo!;`
- [x] `let mensagem = "Olá, mundo!";`
- [ ] `let mensagem = 'Olá, mundo!";`

### Questão 5
Para que serve uma variável em programação?
- [ ] Executar funções
- [ ] Escrever comentários
- [x] Armazenar dados
- [ ] Criar documentos HTML

## Questões Discursivas

### Questão 1
Explique a diferença entre `var`, `let` e `const` na declaração de variáveis em JavaScript.

### Questão 2
Descreva um cenário onde seria mais apropriado usar o tipo `const` ao invés de `let` ou `var`.

### Questão 3
Como você pode concatenar strings e variáveis para criar uma mensagem personalizada em JavaScript? Dê um exemplo.

## Atividades Práticas ou Projetos

### Atividade 1
Crie um pequeno script que peça ao usuário sua idade e nome, e então imprima uma mensagem na tela dizendo: "Olá, [nome]! Você tem [idade] anos."

### Atividade 2
Desenvolva um programa que use variáveis para armazenar as informações de três produtos (nome, preço e quantidade em estoque) e que imprima essas informações de forma clara e organizada.

## Gabarito ou Rubrica de Avaliação

### Múltipla Escolha
1. C
2. B
3. B
4. C
5. C

### Questões Discursivas
1. `var` tem escopo de função ou global e pode ser redeclarada. `let` tem escopo de bloco e não pode ser redeclarada. `const` também tem escopo de bloco, não pode ser redeclarada e deve ser inicializada na declaração.
2. `const` deve ser usado quando o valor atribuído à variável não deve mudar ao longo do programa, como o número de dias em uma semana.
3. Exemplo: `let nome = "Maria"; let saudacao = "Olá, " + nome + "!"; console.log(saudacao);` - Isso imprimiria "Olá, Maria!".

### Avaliação das Atividades Práticas
Avalie se o código está correto e executa conforme esperado. Verifique se as variáveis são usadas apropriadamente e se a saída é clara e correta.