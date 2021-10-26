Tabela de conteúdos
=================
<!--ts-->
   * [About](#About)
   * [Usage](#Usage)
   * [Contributing](#Contributing)

<!--te-->

********************************************************************************

# About

ReplaceCSV is a python library for replacing strings in a CSV file. It was created by the need to exchange values that had a comma for a dot (Ex.: 14,592 >> 14.592).

## Usage

```python
from replaceCSV import replaceCSV

#Syntax
replaceCSV(nome_do_arquivo (string), char_q_vai_sair (string), char_q_vai_entrar (string))

#Example of use
replaceCSV('dados.csv', ',', '.')


```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
