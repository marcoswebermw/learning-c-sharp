## Conversões em C#
  
Assim como em outras linguagens, C# trás mecanismos de conversão de determinados tipos para outros.  
  
> Em vários exemplos aqui, são usados métodos estáticos da classe `System.Convert`.  

### Inteiro para String
  
Parecido com o `toString()` do Java. Pode ser sobrescrito. Pertence a classe `Object`, que significa que todas as classes o tem.  
  
`valor_inteiro.ToString();`    

A string pode ser formatada para um estilo numérico:  
  
`valor_inteiro.ToString("N");`  
    

### Inteiro para String - Usando a classe `System.Convert`  
  
`System.Convert.ToString(valor_inteiro)`  
  
### String para Inteiro
    
`System.Convert.ToInt32(valor_string);`  
   
### String para Double

`System.Convert.ToDouble(valor_string);`  
     

  
### Referências
  
* [MSDN Convert](https://msdn.microsoft.com/pt-br/library/system.convert(v=vs.110).aspx)  
* [MSDN ToString()](https://msdn.microsoft.com/pt-br/library/system.object.tostring(v=vs.110).aspx?cs-save-lang=1&cs-lang=csharp#code-snippet-1)  

