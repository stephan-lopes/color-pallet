# Color Pallet
*Paleta de Cores que podem ser usadas com Bash*

## Como usar?
Para usar, basta executar um dos seguintes comandos em seu terminal: 

- Usando o `curl`:
```bash
curl https://raw.githubusercontent.com/stephan-lopes/color-pallet/main/colorpallet.sh | bash
```

- Usando o `wget`:
```bash
wget https://raw.githubusercontent.com/stephan-lopes/color-pallet/main/colorpallet.sh --output-document - | bash - 
```

- Usando o `git`:
```bash
git clone git@github.com:stephan-lopes/color-pallet.git
/usr/bin/env bash color-pallet/colorpallet.sh
```

## Para que serve?
A finalidade é bem questionável. Pode ser para ter o nomes das cores, pois se você usar o nome gerado por elas, o shell acaba incorporando a cor do texto específico. Pode ser usado no Tmux por exemplo, para colocar uma das 256 cores pré-definidas. Uma curiosidade, é que o padrão inglês `colour` pode ser substituido por `color` que não resultará em problemas, nas versões mais recentes.Enfim, o uso, somente quem vai usar poderá dizer. Mas se precisar saber do nome de todas as cores, basta executar o script.
