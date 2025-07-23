# Trabalho-de-Linguagem-de-Programa-o
Fundamentos-Linguagens-UFC/
│
├── README.md                         
Este repositório reúne a resolução dos 14 desafios propostos na disciplina de Linguagens de Programação, com foco na aplicação prática dos principais conceitos estudados ao longo do curso.
Cada desafio aborda um tema fundamental da área, explorado de forma autorais, criativa e contextualizada, utilizando diferentes linguagens de programação e formas de apresentação, como textos explicativos, códigos, diagramas, quadros comparativos e scripts.

├── 01-introducao/                      --> README.md com linha do tempo da evolução das linguagens
# Linha do Tempo da Evolução das Linguagens de Programação

| Ano   | Linguagem        | Descrição                                                                                     |
|-------|------------------|-----------------------------------------------------------------------------------------------|
| 1957  | 🧮 Fortran       | Primeira linguagem de alto nível, criada para cálculos científicos e engenharia.              |
| 1958  | 🔷 Lisp          | Pioneira em programação funcional e inteligência artificial, com manipulação de listas.      |
| 1959  | 🏦 COBOL         | Voltada para aplicações comerciais e bancárias, muito usada em sistemas legados.              |
| 1964  | 🧠 BASIC         | Desenvolvida para ensino e iniciantes, facilitou a popularização da programação.              |
| 1967  | 🔶 Simula        | Introduziu o paradigma orientado a objetos, base para linguagens como C++ e Java.             |
| 1970  | 📚 Pascal        | Foco em boas práticas e ensino estruturado da programação.                                   |
| 1972  | 🧱 C             | Base para sistemas operacionais como Unix, influenciou muitas linguagens modernas.            |
| 1978  | ⚙️ Prolog        | Linguagem lógica para inteligência artificial e processamento simbólico.                     |
| 1980  | 🔄 Smalltalk     | Uma das primeiras linguagens orientadas a objetos puras, influenciou Python e Ruby.          |
| 1983  | 🧩 C++           | Extensão do C com suporte a orientação a objetos e software de alto desempenho.               |
| 1987  | 🧵 Perl          | Linguagem de script para automação, processamento de texto e web.                            |
| 1991  | 🐍 Python       | Simples, legível e versátil, usada em ciência de dados, IA, automação e web.                  |
| 1993  | 🔥 Ruby          | Focada em simplicidade e produtividade, linguagem orientada a objetos, popular com Rails.    |
| 1995  | ☕ Java          | “Escreva uma vez, rode em qualquer lugar”. Popular em sistemas empresariais e Android.       |
| 1995  | 🌐 JavaScript    | Linguagem para interação web, hoje também usada no backend com Node.js.                      |
| 1995  | 💾 PHP           | Linguagem server-side para desenvolvimento web dinâmico.                                    |
| 2000  | 🧿 C#            | Criada pela Microsoft para o .NET, usada em aplicações desktop, web e jogos.                  |
| 2001  | 🐦 Objective-C   | Popular para desenvolvimento de apps Apple antes do Swift.                                  |
| 2009  | 🚀 Go            | Desenvolvida pelo Google, ideal para sistemas concorrentes e servidores eficientes.           |
| 2010  | 🔒 Rust          | Segurança de memória e alta performance sem coletor de lixo.                                 |
| 2011  | 💎 Kotlin        | Compatível com Java, mais concisa e segura, oficial para Android.                            |
| 2014  | 🍎 Swift         | Moderna e segura, substitui Objective-C no ecossistema Apple.                                |
| 2015  | 📦 TypeScript    | Superset do JavaScript que adiciona tipagem estática opcional.                               |
| 2020+ | 🌟 Tendências Emergentes | Elixir, Zig, Crystal, Julia e outras ganham espaço com foco em segurança, concorrência e produtividade. |

├── 02-ambientes/                       --> README.md + diagramas de compiladores, interpretadores e VMs
│
![Diagrama do sistema](Diagrama.jpeg)
├── 03-sintaxe-semantica/              --> README.md + mini-gramática fictícia com análise léxica
│
🌱 Linguagem Inventada: MinimaLang

Uma linguagem criada pra ser fácil de entender até pra quem nunca programou. Só 3 comandos principais: guardar, mostrar e somar.

Regras da Linguagem
guarda nome tipo → declara uma variável (tipo pode ser número ou texto)

nome recebe valor → atribui valor à variável

mostra nome → exibe a variável

soma nome1 e nome2 → soma duas variáveis numéricas

SomaNome = nome1 + Nome2 

mostra nome = SomaNome


├── 04-tipos-de-dados/                 --> README.md + comparativo entre tipos de dados em 3 linguagens
│
📚 Tipos de Dados: Comparando C, Java e C#

🔹 Linguagem C

A linguagem C possui tipagem estática, ou seja, os tipos das variáveis são definidos em tempo de compilação. No entanto, sua tipagem é considerada fraca, pois permite muitas conversões implícitas entre tipos diferentes, mesmo que isso possa causar comportamentos inesperados ou erros de execução. Por exemplo, é possível forçar a conversão de uma string para um inteiro com type casting, mesmo que o valor não seja compatível.

🔹 Linguagem Java

Java utiliza tipagem estática e forte. Os tipos das variáveis devem ser declarados, e o compilador verifica se os tipos estão corretos antes de rodar o programa. Não permite conversões implícitas arriscadas. Se você tentar atribuir uma string a uma variável inteira, o código nem vai compilar. Isso torna o código mais seguro e previsível.

🔹 Linguagem C#

C# também possui tipagem estática e forte, mas oferece uma sintaxe mais moderna com suporte a inferência de tipo por meio da palavra-chave var. Mesmo com var, o tipo ainda é determinado em tempo de compilação e não pode ser alterado depois. Como em Java, conversões implícitas perigosas não são permitidas.

├── 05-estruturas-de-controle/         --> README.md + código com estruturas de controle em contexto original
│

├── 06-subprogramas/                   --> README.md + funções com passagem por valor e referência
│

├── 07-implementacao-subprogramas/     --> README.md + explicação e desenho da pilha de chamadas (recursão)
│

├── 08-orientacao-objetos/             --> README.md + modelagem de classes com herança e polimorfismo
│

├── 09-concorrencia/                   --> README.md + explicação de threads/processos + exemplo prático
│

├── 10-gerenciamento-memoria/          --> README.md + quadro comparativo entre dois modelos de memória
│

├── 11-programacao-funcional/          --> README.md + código com recursão e funções de alta ordem
│

├── 12-programacao-logica/             --> README.md + problema lógico modelado em estilo Prolog
│

├── 13-scripts-web/                    --> README.md + script de automação ou manipulação de dados
│

└── 14-tendencias/                     --> README.md + análise crítica sobre linguagem emergente

