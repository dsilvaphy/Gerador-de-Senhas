# Gerador de Senhas 🔒

Um **Gerador de Senhas** interativo desenvolvido em Python, com interface gráfica utilizando a biblioteca `tkinter`. Este programa permite criar senhas seguras e personalizadas de acordo com as preferências do usuário, como incluir letras maiúsculas, números, símbolos e escolher a ordem dos caracteres.

## Funcionalidades

- Geração de senhas seguras e personalizadas.
- Escolha do tamanho da senha.
- Inclusão opcional de:
  - Letras maiúsculas
  - Números
  - Símbolos
- Possibilidade de criar senhas em ordem aleatória ou fixa (letras, números, símbolos).
- Copia automaticamente a senha gerada para a área de transferência.
- Interface gráfica amigável, com diálogos para coletar as preferências do usuário e exibir a senha gerada.

## Pré-requisitos

Certifique-se de ter o Python 3.x instalado. Além disso, instale a biblioteca `pyperclip`, que é usada para copiar a senha para a área de transferência:

```bash
pip install pyperclip
```

## Como usar
1. Clone este repositório ou baixe o arquivo geradorsenhas.py.

2 Execute o script no terminal ou em um editor Python, como o VSCode ou PyCharm:

```bash
Copiar código
python geradorsenhas.py
```
3. Siga as instruções exibidas nas caixas de diálogo:
- Informe o tamanho da senha.
- Escolha as opções desejadas (letras maiúsculas, números, símbolos, ordem aleatória).
4. Ao final, a senha gerada será exibida e automaticamente copiada para a área de transferência. Você poderá colá-la (Ctrl + V) onde desejar.

## Estrutura do Projeto
- geradorsenhas.py: Script principal do gerador de senhas.
Exemplo
1. Perguntas no programa:
- "Digite o tamanho da senha desejada (ex: 12)"
- "Incluir letras maiúsculas?"
- "Incluir números?"
- "Incluir símbolos?"
- "Gerar em ordem aleatória?"
2. Resultado na caixa de diálogo:
Sua senha gerada é: G5#d3K7&
"A senha foi copiada para a área de transferência!"

## Bibliotecas Utilizadas
- random: Para geração de caracteres aleatórios.
- string: Para acessar conjuntos de caracteres (letras, números, símbolos).
- tkinter: Para criar a interface gráfica.
- pyperclip: Para copiar a senha gerada para a área de transferência.

## 📜 Licença

📄 Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar e modificar, exceto para fins comerciais.

Veja a licença completa [CC BY-NC 4.0](/creativecommons.org/licenses/by-nc/4.0/deed.pt-br).

