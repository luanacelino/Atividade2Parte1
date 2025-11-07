## Atividade2Parte1
Essa é a primeira parte da segunda atividade, e nessa atividade vamos responder algumas questões. 

<br>


### Sumario

1. Explique o que é JSON e por que ele se tornou tão popular para troca de dados
entre aplicações.

2.Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um
exemplo prático de quando usar cada um.

3.Considerando a string ```"JavaScript é baseada em ECMA Script"```, quais métodos
você usaria para:
- Verificar se contém a palavra "Script";
- Remover a palavra "JavaScript" e gerar uma nova string;
- Substituir "baseada" por "tem origem"

4. Qual a vantagem de usar template strings (``) em vez de concatenação com +
para criar strings complexas?

<br>
<br>

**1. Explique o que é JSON e por que ele se tornou tão popular para troca de dados
entre aplicações.**

O JSON (JavaScriptObjectNotation) é um formato leve de troca de dados, baseado em texto, que usa uma estrutura parecida com objetos do JavaScript.
Ele é composto por pares de chaves e valor, e serve para armazenar e transmitir informações entre sistemas.

**Exemplo de um JSON**

```
{"nome":"Rodrigo",
 "idade":27,
 "nascimento":"01-11-1998"
}
```
<br>
O JSON se tornou tão popular devida a simplicidade e legibilidade humana.É facil e ler e entender, mesmo para quem nã é programador, a sintaxe é limpa, sem tags complexas. Outro ponto de destaque é a sua compatibilidade com varias linguagens. O JSON não é exlcusivo do JavaScript, ele é suportado por praticamente todas as linguagens de programação (Python, Java, PHP, etc.), o que facilita a comunicação entre sistemas diferentes(a unica ressalva é quando vamos lidar com funções e nesse caso o JSON não vai fazer essa leitura entre uma linguagem e outra)

<br>
**2.Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um
exemplo prático de quando usar cada um.**
