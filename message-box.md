## MessageBox
  
`MessageBox` exibe uma caixa de mensagens a ser exibida para o usuário através do método `Show()`. 
   
### Estrutura
  
`MessageBox.Show("Mensagem", "Título", MessageBoxButtons.OK, MessageBoxIcon.Information);`  
  
Onde:  
  
- "Mensagem" - É uma mensagem que será exibida ao usuário;  
- "Título" - É o título da caixa de mensagem;  
- MessageBoxButtons - São constantes que indicam os botões que aparecerão na caixa;  
- MessageBoxIcon - É o ícone informativo da caixa que indica visualmente o propósito dela.  
  
### Tipos de MessageBoxButtons
  
- AbortRetryIgnore;
- OK;
- OKCancel;
- RetryCancel;
- YesNo;
- YesNoCancel.
  
### Tipos de MessageBoxIcon
  
- Asterisk;
- Error;
- Exclamation;
- Hand;
- Information;
- None;
- Question;
- Stop;
- Warning.  
  
### Exemplos de exibição de botões
  
```cs
private void exibirBotoes()
        {
            MessageBoxButtons[] botoes = new MessageBoxButtons[6];
            botoes[0] = MessageBoxButtons.AbortRetryIgnore;
            botoes[1] = MessageBoxButtons.OK;
            botoes[2] = MessageBoxButtons.OKCancel;
            botoes[3] = MessageBoxButtons.RetryCancel;
            botoes[4] = MessageBoxButtons.YesNo;
            botoes[5] = MessageBoxButtons.YesNoCancel;

            for (int i = 0; i < 6; i++)
            {
                MessageBox.Show("Exibindo Botões:", "Botões", botoes[i], MessageBoxIcon.Information);
            };
        }
```  
  
### Exemplos de exibição de Ícones
  
```cs
        private void exibirIcones()
        {
            MessageBoxIcon[] icones = {
                MessageBoxIcon.Asterisk,
                MessageBoxIcon.Error,
                MessageBoxIcon.Exclamation,
                MessageBoxIcon.Hand,
                MessageBoxIcon.Information,
                MessageBoxIcon.None,
                MessageBoxIcon.Question,
                MessageBoxIcon.Stop,
                MessageBoxIcon.Warning
            };

            for (int i = 0; i < 6; i++)
            {
                MessageBox.Show("Exibindo Ícones:", "Ícones", MessageBoxButtons.OK, icones[i]);
            };
        }
```  