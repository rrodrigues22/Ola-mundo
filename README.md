# Olá mundo! - Título Nível 1
 Repositório curso de Git e GitHub
 
 ## Aula Linguagem Markdown - Título Nível 2
 ***
 __Negrito__ ou **Negrito**
 _Itálico_ ou _Itálico_
 ~~Riscado~~
 
 Podemos __*misturar*__ configurações
 
 Lista numerada:
 1. Item 1
 2. Item 2
    1. Novo Item
    1. Novo Item 2
 200. Item 3

Lista demarcada:
* Teste
* Teste
  * Teste
* Teste

Lista de Tarefas:

- [ ] Tarefa 1
- [ ] Tarefa 2
- [x] Tarefa 3
- [ ] Tarefa 4

![github](https://user-images.githubusercontent.com/118119654/221390637-2391c926-22fe-4ee2-8210-710bb43d04e6.jpg)

[Acesse meu GitHub](https://github.com/rrodrigues22)

Num | Nome | Nota
---|---|---
1 | Roni | 8,9
2 | Teste | 10

Comando `LOOP AT` da linguagem ABAP percorre as linhas de uma tabela interna

Programa teste em ABAP:
```
DATA: purchase_documents TYPE TABLE OF ekko.

SELECT SINGLE * FROM ekko INTO purchase_documents UP TO 3 ROWS.

LOOP AT purchase_documents INTO DATA(purchase_document).

WRITE: purchase_document-ebeln.

ENDLOOP.
```
