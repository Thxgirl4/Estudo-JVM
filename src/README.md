
# JVM a poderosa Maquina Virtual do Java

## Máquina Virtual:
A JVM funciona como uma máquina virtual, simulando o comportamento de uma máquina física. Ela gerencia a execução do código Java, cuida de tarefas como gerenciamento de memória, execução de threads, e até a coleta de lixo (Garbage Collector), facilitando a vida dos desenvolvedores ao cuidar de detalhes do sistema operacional subjacente.
![image](https://github.com/user-attachments/assets/6bd9ef67-4270-4073-a125-1763a4774b72)


## Portabilidade do Java:
A famosa frase "write once, run everywhere" (escreva uma vez, rode em qualquer lugar) é possível graças à JVM. A linguagem Java é compilada para um código intermediário, chamado ByteCode, que pode ser interpretado e executado em qualquer plataforma onde a JVM esteja instalada, independentemente do sistema operacional.

Esse código é o que será traduzido pela Virtual Machine para o código de cada máquina em questão. Os processos de execução de um software Java foram aperfeiçoados ao longo dos tempos, pois no início, a Virtual Machine interpretava apenas um ByteCode por vez. Hoje em dia, a JVM possui sistemas de compilação JIT (Just - In - Time) misturados com a interpretação do código. Essa técnica cria os chamados “Hot-Spots”, que nada mais são que áreas de código executadas com maior frequência. Isso ocorre com a análise dos ByteCodes à medida que eles são interpretados pela Virtual Machine.

![image](https://github.com/user-attachments/assets/ac3d5f4d-1126-4e00-bf61-a4d05a062a60)

## JDK vs. JRE:
- O JDK (Java Development Kit)
  é o kit de desenvolvimento necessário para programadores, pois contém ferramentas para escrever, compilar e testar código Java. Ele já inclui a JVM.

- O JRE (Java Runtime Environment)
  é necessário para executar programas Java em qualquer dispositivo. Ele contém a JVM e bibliotecas essenciais para a execução de programas Java, mas não inclui as ferramentas de desenvolvimento.

![image](https://github.com/user-attachments/assets/956a1507-44c0-4b4e-93f9-888e8f324d07)
