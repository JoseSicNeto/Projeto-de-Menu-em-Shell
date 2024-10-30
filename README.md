# Projeto Universitário de Manipulação de Arquivo Shell

## Descrição da Atividade

O projeto consiste na criação e manipulação de três arquivos:
- **Arq1**: Contém 10 nomes.
- **Arq2**: Contém 10 cidades.
- **Arq3**: Contém 10 linhas com os campos: telefone, CEP, estado, região e DDD. Todos os campos são delimitados por ponto-e-vírgula (;).

## Menu Interativo

O script oferece um menu interativo com as seguintes opções no menu principal:
- **1 - Métodos de Arquivo**: Acessa o menu de métodos de manipulação dos arquivos.
- **2 - Exibição de Arquivos**: Acessa o menu de exibição dos arquivos criados.
- **0 - Sair do Programa**: Fecha o menu e encerra o script.

### Menus dos Scripts

- **Main**: Script principal que contém o menu principal e redireciona para os outros scripts (Display, Methods ou encerra o programa).
- **Display**: Contém um menu para escolher qual arquivo exibir (Arq1, Arq2, Arq3...).
- **Methods**: Contém um menu com opções de manipulação dos arquivos, incluindo:
  - **Inserir Dados nos Arquivos 1 e 2**: Permite adicionar nomes no Arq1 e abreviações de estados brasileiros no Arq2.
  - **Criar Arquivo 4 a partir do Arquivo 3**: Seleciona campos específicos do Arq3 para criar um novo arquivo.
  - **Criar Arquivo 5 com Linhas Selecionadas**: Escolhe linhas específicas do Arq1 ou Arq2 para criar um novo arquivo.
  - **Capitalizar Texto em um Arquivo**: Converte todo o texto de um arquivo selecionado para maiúsculas ou minúsculas.
  - **Remover Linhas Duplicadas de um Arquivo**: Remove duplicatas do Arq1 ou Arq2 e gera um novo arquivo.
  - **Combinar Arquivos 1 e 2**: Junta o conteúdo de ambos os arquivos em um novo arquivo.
  - **Voltar para o Menu Principal**: Retorna ao menu principal no `Main`.

### Função de Manipulação de Erros

O script inclui uma função que exibe mensagens de erro e utiliza manipulação de cursor para limpar entradas falhas. Isso garante que a tela não fique poluída com entradas inválidas, melhorando a usabilidade.

## Como Executar

1. Clone este repositório:
    ```bash
    git clone https://github.com/JoseSicNeto/Projeto-de-Menu-em-Shell.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd Projeto-de-Menu-em-Shell/Program
    ```
3. Torne o script executável:
    ```bash
    chmod +x Main
    ```
4. Execute o script:
    ```bash
    ./Main
    ```

## Estrutura do Projeto

- `Main`: Script principal que contém o menu e as funções para manipulação dos arquivos.
- `Display`: Script que contém funções para exibição dos arquivos.
- `Methods`: Script que contém as funções de manipulação dos arquivos.

## Contato

Para dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

- **Email**: seuemail@dominio.com
- **LinkedIn**: [Seu Perfil](https://www.linkedin.com/in/seu-perfil)
