# java-11-notes

## Criando classes no Java
Todo o codigo é definido em classes, que sao defindas em código fonte .java.

O comando *javac* compila o codigo java em bitecode

O comando *java* roda os arquivos compilados

Exemplo de classe simples

```java
package com.example
public class Main {
    public static void main(String[] args){
        System.out.println("exemplo simples em java")
    }
}
```

## Algumas novidades de Sintaxe

- **Exception Handling**: Java usa blocos try, catch, and finally blocks para lidar com exceptions e errors.
- **Generics**: Java 11 suporta generics, que permite criar classes, interfacese metodosque operam em objetos de vários tipos, ao mesmo tempo que fornece segurança de tipo em tempo de compilação.

- **Lambda Expressions**: Java 11 introduziu lambda expressions,que permitem expressar instâncias de interfaces de método único (chamadas de interfaces funcionais) de forma mais concisa

- **Modules**: Java 9 introduziu o sistema de módulos, que permite criar aplicativos e bibliotecas modulares. Java 11 continua a oferecer suporte a esse recurso, permitindo dividir seu código em módulos para melhor organização e encapsulamento

## Convenções

- Classes começam sempre com letra maiúscula, e no restante, camel case.
- Métodos e variáveis começam com letra minúscula
- Constantes em caixa alta

## Gerenciamento de memória

- A memória é alocada e desalocada automaticamente;
- Objetos são retidos na memória até que sejam "desreferenciados" e são elegiveis ao coletor de lixo quando perdem sua referência;
- Variáveis locais e chamadas de funções são armazenadas na memória stack;
- Objetos e variáveis de instancia são armazenadas na memoria heap;
> Variáveis de instância são declaradas dentro de uma classe, mas fora de um método, construtor ou bloco e sempre obtêm um valor padrão.
  
### Garbage collector
(in progress)

## Referências
[New Features in Java 11](https://www.baeldung.com/java-11-new-features)
[DIFERENÇA ENTRE VARIÁVEL DE INSTÂNCIA E VARIÁVEL LOCAL](https://acervolima.com/diferenca-entre-variavel-de-instancia-e-variavel-local/)
