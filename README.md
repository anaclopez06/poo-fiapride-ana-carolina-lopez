# Projeto Sistema de Biblioteca - Ana Carolina Pereira Lopez

## Informações do Aluno

- **Nome:** Ana Carolina Pereira Lopez
- **RM:** 568401
- **Turma:** 2CCPS
- **Curso:** Ciência da Computação
- **GitHub:** @anaclopez06

---

## Descrição do Projeto

Este projeto é um sistema de biblioteca, o sistema permite cadastrar livros e usuários, consultar a disponibilidade de livros, registrar empréstimos e devoluções e apresentar um resumo do empréstimo. 

---

## Checklist de Implementação

- [x] Aula 1 - Classes e Objetos
- [x] Aula 2 - Métodos
- [x] Aula 3 - Encapsulamento
- [x] Aula 4 - Construtores
- [x] Aula 5 - Associação
- [x] Aula 6 - Herança
- [x] Aula 7 - Polimorfismo
- [x] Aula 8 - Classes Abstratas
- [x] Aula 9 - Interfaces

---

## Perguntas de Reflexão

### Aula 1 - Classes e Objetos

Criar uma classe para representar o usuário ajuda a organizar as informações de cada pessoa em um só lugar. Se eu criasse várias variáveis separadas no main, ficaria mais difícil organizar tudo, principalmente se tivesse muitos usuários. Com a classe Usuario, posso criar vários usuários usando a mesma estrutura, deixando o código mais organizado e fácil de entender.

### Aula 2 - Métodos

Os métodos servem para fazer algumas ações dentro do programa. Por exemplo, no nosso projeto, o método emprestar() verifica se o livro está disponível antes de realizar o empréstimo. Assim, evitamos que o mesmo livro seja emprestado quando já está com outra pessoa. Isso também ajuda a deixar o código mais organizado, porque cada método fica responsável por uma ação.

### Aula 3 - Encapsulamento

O encapsulamento serve para proteger os atributos de uma classe. No nosso projeto, os atributos de Livro são privados, então não podem ser acessados diretamente de qualquer parte do programa. Para consultar essas informações, usamos métodos como os getters. Isso ajuda a evitar que os dados sejam alterados de qualquer jeito e deixa o sistema mais organizado.

### Aula 4 - Construtores

Os construtores servem para definir como um objeto vai ser criado. No nosso projeto, o construtor de Livro recebe o título e o autor e define que o livro começa disponível. Depois, usamos os métodos emprestar() e devolver() para mudar essa situação. Assim, as mudanças acontecem por meio de ações do sistema, em vez de alterar os atributos diretamente.

### Aula 5 - Associação

A associação acontece quando uma classe se relaciona com outra. No nosso projeto, a classe Emprestimo possui um objeto Livro e um objeto Usuario. Isso é importante porque precisamos saber qual livro foi emprestado e quem pegou esse livro. Se guardássemos apenas o nome do usuário como texto, seria mais difícil relacionar o empréstimo com as informações e os métodos do próprio usuário. Dessa forma, as classes conseguem trabalhar juntas dentro do sistema.

### Aula 6 - Herança

A herança permite que uma classe aproveite algumas coisas de outra classe, como atributos e métodos. Porém, se um atributo for privado, a classe filha não pode acessar ele diretamente. No nosso projeto, a classe Usuario herda de Pessoa e usa métodos como getNome() para acessar as informações. Assim, conseguimos reaproveitar o código sem deixar os dados desprotegidos.

### Aula 7 - Polimorfismo

O polimorfismo permite que um mesmo método funcione de formas diferentes dependendo da classe. Para isso, o método precisa estar definido na classe principal ou na interface usada como referência. No nosso projeto, a classe Pessoa tem o método apresentarDados() e a classe Usuario implementa esse método mostrando o nome e o código do usuário. Dessa forma, cada classe pode apresentar suas informações do seu jeito.

### Aula 8 - Classes Abstratas

Uma classe abstrata é uma classe que não pode ser usada diretamente para criar um objeto. Ela serve como uma base para outras classes. No nosso projeto, Pessoa é abstrata porque representa algo mais geral e tem o método apresentarDados(), que precisa ser implementado pelas classes que herdam dela. Usamos abstract para indicar isso ao Java.

### Aula 9 - Interfaces

Em Java, uma classe só pode herdar diretamente de uma outra classe, mas pode implementar várias interfaces. As interfaces servem para definir métodos que uma classe precisa ter. No nosso projeto, Usuario implementa a interface Notificavel e, por isso, possui o método enviarNotificacao(). Assim, a interface define o que a classe precisa fazer, mas a própria classe escreve como esse comportamento vai funcionar.

---

## Desafios Técnicos Implementados

### Desafio Pessoal (Seu Projeto)

**Qual foi o domínio que você escolheu para seu projeto pessoal?**

Escolhi o de um sistema de biblioteca, com controle de livros, usuários, empréstimos e devoluções.

**Quais classes você criou?**

- `Livro`: representa os livros e controla sua disponibilidade.
- `Pessoa`: classe abstrata com dados comuns de uma pessoa.
- `Usuario`: representa o usuário da biblioteca e herda de `Pessoa`.
- `Emprestimo`: relaciona um livro a um usuário e controla o estado do empréstimo.
- `Notificavel`: interface que define o comportamento de envio de notificações.
- `BibliotecaApp`: classe principal com os testes do sistema.

**Qual foi o maior desafio técnico que você enfrentou?**

Saber exatamente quais comandos fazem cada coisa e que na hora de montar a estrutura do código ela fizesse sentido.

---

## Conclusão

**O que você aprendeu nestas 9 aulas?**

Aprendi um pouco mais sobre como funciona a programação orientada a objetos em Java. Aprendi a criar classes e objetos, usar métodos e organizar melhor o código. Também entendi como funciona o encapsulamento, a herança, o polimorfismo, as classes abstratas e as interfaces. Ainda tenho um pouco de dificuldade para programar sozinha, mas, desenvolvendo o projeto da biblioteca, consegui entender melhor como esses conceitos funcionam na prática e como as classes podem trabalhar juntas para formar um sistema.

**Qual conceito foi mais difícil de entender?**

O conceito que achei mais difícil de entender foi o encapsulamento, principalmente a parte dos getters e setters. Ainda tenho um pouco de dificuldade para entender como e quando usar cada um, então precisei pedir ajuda para a IA me ajudar e explicar de um jeito mais fácil. Mesmo assim, ainda estou tentando praticar para entender melhor como funciona.

**O que você melhoraria no seu projeto se pudesse refazer?**

Se eu pudesse refazer o projeto, gostaria de incluir mais funcionalidades, como cadastrar vários livros e usuários, pesquisar livros pelo título e mostrar quais livros estão disponíveis ou emprestados. Também gostaria de melhorar a organização do código e praticar mais os conceitos de POO para conseguir desenvolver algumas partes sozinha, sem precisar de tanta ajuda.
