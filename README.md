
[![Classe String](https://img.shields.io/badge/-Classe%20String-007acc?style=flat&logoColor=white)](#classe-string-em-java)

[![Classe Object](https://img.shields.io/badge/-Classe%20Object-007acc?style=flat&logoColor=white)](#classe-object) - Em Breve 

[![Classe StringBuilder](https://img.shields.io/badge/-Classe%20StringBuilder-007acc?style=flat&logoColor=white)](#classe-stringbuilder) - Em Breve

[![Classe StringBuffer](https://img.shields.io/badge/-Classe%20StringBuffer-007acc?style=flat&logoColor=white)](#classe-stringbuffer) - Em Breve 

[![Classe Math](https://img.shields.io/badge/-Classe%20Math-007acc?style=flat&logoColor=white)](#classe-math) - Em Breve  

[![Classe Integer](https://img.shields.io/badge/-Classe%20Integer-007acc?style=flat&logoColor=white)](#classe-integer) - Em Breve  

[![Classe System](https://img.shields.io/badge/-Classe%20System-007acc?style=flat&logoColor=white)](#classe-system) - Em Breve  

[![Classe Runtime](https://img.shields.io/badge/-Classe%20Runtime-007acc?style=flat&logoColor=white)](#classe-runtime) - Em Breve 

[![Classe Exception](https://img.shields.io/badge/-Classe%20Exception-007acc?style=flat&logoColor=white)](#classe-exception) - Em Breve  

---
  # Classe String em Java
A classe String é uma das mais fundamentais da linguagem Java, utilizada para representar sequências de caracteres (textos). Ela pertence ao pacote java.lang e é imutável, o que significa que seu conteúdo não pode ser alterado após a criação do objeto.

## 🚀 Características Principais

✅ Imutabilidade: Toda operação sobre uma String cria um novo objeto. Isso melhora a segurança e a previsibilidade.

✅ Classe Final: A classe String é final, o que significa que não pode ser estendida.

✅ Interning: Strings literais são armazenadas no String Pool, otimizando o uso de memória.

✅ Compatível com métodos de comparação, busca, substituição, divisão e conversão.

## 🔧 Criação de Strings
 

```
String texto1 = "Java";
```
```         
String texto2 = new String("Java");
```
Para melhor desempenho e simplicidade, prefira sempre literals.

## 📚 Principais Métodos

### Método	Descrição:
 
**length()** -	Retorna o número de caracteres
**charAt(int index)** - 	Retorna o caractere no índice especificado.

`substring(int beginIndex)` - Retorna uma nova String a partir de um índice.

`equals(Object obj)` - Compara o conteúdo da String com outro objeto.

`equalsIgnoreCase(String)` -	Compara ignorando maiúsculas e minúsculas.

`contains(CharSequence)` -	Verifica se uma sequência está contida na String.

`replace(CharSequence, ...)` -	Substitui partes da String.

`split(String regex)` -	Divide a String com base em uma expressão regular.

`toUpperCase()` -	Converte para letras maiúsculas.

`toLowerCase()` -	Converte para letras minúsculas.

`trim()` -	Remove espaços no início e fim.

👉 [Veja a documentação oficial completa dos métodos](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/String.html#method-summary).

## ⚖️ Comparação de Strings

 `==`  compara referência (endereços de memória).

`equals()` compara conteúdo textual.

`compareTo()` compara lexicograficamente e retorna:

`0` se forem iguais,

  valor negativo se a String for menor,

  valor positivo se for maior.

```
String a = "Java";
String b = "Java";

System.out.println(a == b);       // true (referência igual por ser literal)
System.out.println(a.equals(b));  // true (conteúdo igual)
```

## 🧪 Strings e Expressões Regulares
A classe String é compatível com expressões regulares, facilitando tarefas como validações e extrações:

```
String email = "exemplo@email.com";
boolean valido = email.matches("^[\\w.-]+@[\\w.-]+\\.\\w+$");
```

## 🛡️ Segurança e Performance
Por ser imutável, String é segura para uso em ambientes concorrentes.

Para operações intensivas com texto, utilize StringBuilder ou StringBuffer.

## 🧠 Dica de Boas Práticas

Evite usar new String(...) desnecessariamente.

Prefira o uso de StringBuilder em loops.

Sempre use equals() ao comparar strings, nunca ==.

## 📎 Links Úteis

📖 [Documentação oficial da classe String](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/String.html)

## 📄 [Guia sobre Strings da Oracle]

## 🧵 [Java String Pool](https://docs.oracle.com/javase/tutorial/java/data/strings.html)

## 📚 Comparação entre String, StringBuilder e StringBuffer


# Diagrama da Classe *String*
---
<p align="center">
  <img src="https://github.com/user-attachments/assets/1c5eb3ac-291c-4882-a1cd-586966f5e12d" height="400" width="700"/>
</p>
