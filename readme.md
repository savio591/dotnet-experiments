# .NET Experiments
Meu primeiro contato com o ecossistema .NET <3

**Abaixo rascunhos teóricos sobre dotnet**

---

## Estrutura do programa C#

Os principais conceitos organizacionais em C# são:

- Programas
- Namespaces
- Tipos
- Membros
- *Assemblies*

---

- Programas em C# consistem em um ou mais arquivos
- Os programas declaram **tipos**, que contêm **membros** e podem ser organizados em **namespaces**
- **Classes** e **interfaces** são exemplos de **tipos**
- **Campos**, **métodos**, **propriedades** e **eventos** são exemplos de **membros**

Quando os programas C# são compilados, eles são fisicamente empacotados em assemblies

Os assemblies geralmente têm a extensão de arquivo .exe ou .dll, dependendo se são aplicações ouiotecas

## Tipos de valor
Variáveis de tipos de valor contêm diretamente seus dados

As variáveis têm sua própria cópia dos dados e não é possível que as operações afetem outra variável( exceto no caso das variáveis de parâmetro *ref* e *out* )

* **Numéricos:** sbyte, short, int, long, byte, ushort, uint, ulong
* **Caracteres Unicode**: char
* **Pontos flutuantes:** float, double, decimal
* **Booleano**: bool
* **Outros:** enum, struct e tipos nullable (exemplo int?)

## Tipos de referência

Variáveis de tipos de referência armazenam referências a seus dados.

É possível que duas variáveis façam referência ao mesmo objeto e, portanto, que operações em uma variável afetem o objeto referenciado pela outra variável.

**Tipos Classe**: class, object, string
**Tipos Arrays**: int[], int[,], etc...
interface, delegate