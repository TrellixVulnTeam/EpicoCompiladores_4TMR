# Épico de Compiladores - Operador pipe para Python

### Aluno: Henrique Martins de Messias
### Matrícula: 17/0050394

## Descrição

O interpretador do Python foi modificado para possuir o operador **pipe** implementado, para que chamadas de função possam ser feitas de uma maneira diferente.

## Modificações

Os seguintes arquivos sofreram alterações:
- [Grammar](https://github.com/Henrike100/EpicoCompiladores/blob/master/Grammar/Grammar)
- [Tokens](https://github.com/Henrike100/EpicoCompiladores/blob/master/Grammar/Tokens)
- [ast.c](https://github.com/Henrike100/EpicoCompiladores/blob/master/Python/ast.c)

As mudanças estão entre os seguintes comentários nos arquivos Grammar e ast.c:
```bash
 # Inicio das Mudanças
    ...
    código
    ...
 # Fim das Mudanças
```
