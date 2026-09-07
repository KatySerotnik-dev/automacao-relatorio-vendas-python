# Automação de Relatório de Vendas com Python

Projeto de automação de processos (RPA) que simula a rotina diária de um analista: baixar os dados de vendas do dia anterior, calcular os principais indicadores e enviar um relatório por e-mail para a diretoria.

## O que o script faz

1. **Acessa o sistema** (Google Drive) e baixa a base de vendas automaticamente
2. **Calcula os indicadores** com pandas:
   - Faturamento total
   - Quantidade de produtos vendidos
3. **Envia o relatório por e-mail**, com o texto já formatado, usando automação de mouse e teclado

## Tecnologias utilizadas

- Python
- [pandas](https://pandas.pydata.org/) — leitura e análise da base de dados
- [pyautogui](https://pyautogui.readthedocs.io/) — automação de mouse e teclado
- [pyperclip](https://pypi.org/project/pyperclip/) — manipulação da área de transferência

## Sobre o projeto

Este foi meu primeiro projeto prático de automação com Python, desenvolvido como exercício de aprendizado, unindo lógica de programação com um caso de uso real do dia a dia de um analista.

## Observação

O script depende de coordenadas de tela (posições de clique) e de um arquivo Excel local, então precisa de ajustes para rodar em outra máquina.
