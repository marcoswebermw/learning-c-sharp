## Estrutura Condicional
  
### Condicional 1
    
```cs
if ( x==2 || x == 10 )
{
    MessageBox.Show("Olá Mundo!", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
}
```
  
### Condicional 2
  
```cs
if ( x==2 || x == 10)
{
    MessageBox.Show("Olá Mundo!", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
} else
{
    MessageBox.Show("Falhou", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
}
```
  
### Condicional 3
  
```cs
if ( x==2 || x == 10)
{
    MessageBox.Show("Olá Mundo!", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
} else if( x==0 )
{
    MessageBox.Show("Oi Mundinho!", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
} else
{
    MessageBox.Show("Falhou", "Alerta", MessageBoxButtons.OK, MessageBoxIcon.Information);
}
```
  