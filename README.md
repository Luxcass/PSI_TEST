# Teste de PSI Modelo

## Informação do aluno

    Nome: Lucas Fernandes de Araújo 

Teste termina às 09:40 (Turno 1) / 13:25 (Turno 2).

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### 1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    char c = '\u00AE';
    Console.WriteLine($@"\n{c}\n");

P1 - Resposta

    É impresso "\n®\n".

### 2. Considera o seguinte código

    double d = 0.3513;
    float f = 12.645;

    Console.WriteLine($"{d} + {f} = {d + f}");

### Indica a correção necessária para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

     double d = 0.3513;
    float f = 12.645F;

    Console.WriteLine($"{d} + {f} = {d + f}");
    Temos que adicionar um "F" no final do número float.
    
### 3. Escreve um programa que solicite uma string ao utilizador, e seguidamente a mostre no ecrã de forma invertida

P3 - Resposta

    ...

### 4. Quais são os comandos Git para configurares, de uma forma global, o teu **nome** e **email** para realização de *commits*? E se essa configuração for apenas para um repositório?

P4 - Resposta

    git config --global user.name "Nome Apelido"
    git config --global user.name "nome.apelido@gmail.com"

    git remote add origin https://...
    git branch -M main 
    git push -u origin main 
