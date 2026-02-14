## 🕒 Conversor de Horário em Java (Herança e Abstração)
# 📌 Sobre o Projeto

Este projeto é uma aplicação desenvolvida em Java com o objetivo de converter um horário informado pelo usuário (horas, minutos e segundos) para:

🇧🇷 Formato Brasileiro (24 horas)

🇺🇸 Formato Americano (12 horas com AM/PM)

O foco principal do projeto é aplicar conceitos de Programação Orientada a Objetos (POO), especialmente:

✔️ Herança

✔️ Abstração

✔️ Polimorfismo

## 🎯 Objetivo

Demonstrar na prática como utilizar classes abstratas e herança para modelar diferentes formatos de horário a partir de uma estrutura base comum.

## 🧠 Conceitos Aplicados
# 🔹 Abstração

Foi criada uma classe abstrata que define a estrutura básica de um horário, contendo:

Atributos: hora, minuto e segundo

Método abstrato para exibir o horário formatado

# 🔹 Herança

Duas classes concretas herdam da classe abstrata:

BRClock
USClock

Formato12Horas

Cada uma implementa o método de exibição conforme sua regra específica.

# 🔹 Polimorfismo

O método de exibição é sobrescrito nas classes filhas, permitindo comportamentos diferentes a partir da mesma estrutura base.

## 🏗 Estrutura do Projeto
```src/
 ├── Clock.java (classe abstrata)
 ├── BRClock.java
 ├── USClock.java
 └── Main.java
```
## ⚙️ Funcionamento

O usuário informa:

Hora

Minuto

Segundo

O sistema:

Exibe o horário no formato 24h (ex: 18:30:45)

Exibe o horário no formato 12h (ex: 06:30:45 PM)

## 💻 Exemplo de Saída

Entrada:
```
Hora: 18
Minuto: 30
Segundo: 45
```

Saída:
``` 
Formato Brasileiro (24h): 18:30:45
Formato Americano (12h): 06:30:45 PM
``` 
## 🚀 Como Executar

Clone o repositório:

git clone <url-do-repositorio>


Abra o projeto em sua IDE (Eclipse, IntelliJ ou VS Code)

Execute a classe Main.java

## 📚 Finalidade Acadêmica

Este projeto foi desenvolvido com fins educacionais para reforçar o aprendizado de:

Programação Orientada a Objetos

Estruturação de classes

Reutilização de código

Organização de projetos Java
