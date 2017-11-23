## Linguagem C#
  
### Soluções
  
Para o C# soluções são como projetos, mas dentro tem vários outros projetos. Serve para organizar vários projetos que servirão como uma solução para o problema enfrentado. Resumindo é uma estrutura de diretórios onde ficam vários projetos relacionados.  
  
```
---Solução_X
   ---Projeto_1
      ---Form1.cs
      ---Program.cs
   ---Projeto_2
      ---Form1.cs
      ---Program.cs   
   ---Projeto_3
      ---Form1.cs
      ---Program.cs   
```
   

### NameSpace
  
O namespace serve para definir, ou qualificar, logicamente as classes em uma estrutura de árvore. Seria o equivalente aos pacotes em Java. Cada classe possui um nome qualificado como por exemplo: 'MeuProjeto.Form1'.  
  

### Partial class
  
No C# existe o conceito de `partial class` que permite que uma classe possa ter vários arquivos para sua definição. Isso é permitido através da palavra reservada `partial`.  
  
**Exemplo de código C#**
  
```cs
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Projeto1
{
    public partial class frmMinhaAplicacao : Form
    {
        // Construtor
        public frmMinhaAplicacao()
        {
            InitializeComponent();
        }

        // Evento
        private void button1_Click(object sender, EventArgs e)
        {

        }
    }
}

```