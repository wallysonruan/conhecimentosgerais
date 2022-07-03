# GOOGLE PLANILHAS E EXCEL
Abaixo estarão aplicações que são aceitas tanto pelo Google Planilhas quanto pelo Excel.

## Como aplicar uma formatação condicional em uma linha inteira usando o resultado de uma célula apenas?
 
Basta aplicar uma formatação condicional regular, e no wizard (caixa de criação e edição da fc) selecionar o intervalo ao qual deseja aplicar a formatação. Selecionado o intervalo, escolha a opção `A fórmula personalizada é` no campo **Regras de formatação**.

Para facilitar o entendimento, utilizarei a imagem abaixo como exemplo.

![PRINT DE USO DA FÓRMULA](https://github.com/wallysonruan/conhecimentosgerais/blob/main/gplanilhas1.jpg)

Perceba que todas as células estão vazias, exceto as D1:D5, e justamente suas respectivas linhas foram afetadas.

Para a situação desse item, a sintaxe obrigatória da fórmula personalizada é: `=$(cód1)1=(cód2)`
- cód1 = Letra da coluna na qual a célula contendo o valor que validará a formatação condicional estará;
- cód2 = Situação lógica que determinará qual será o valor que a célula cód1 tem de ter para que a formatação seja aplicada;
- O número `1` logo após o cód1 serve como indexador de aplicação da formatação. Veja na imagem abaixo o que acontece quando altero o `1` para `3`.

![PRINT DE USO DA FÓRMULA](https://github.com/wallysonruan/conhecimentosgerais/blob/main/gplanilhas2.jpg)
