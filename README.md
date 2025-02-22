<h1>Modificador de Palavras em Arquivos TXT</h1>
Este script Bash modifica o conteúdo de arquivos de texto (.txt), adicionando "X" no início e no final de cada palavra.

<h2>Pré-requisitos</h2>
Distribuição Linux Conectiva 10 (ou similar)
Editor de texto Vi

<h2>Como usar</h2>
<h3>Crie um arquivo de texto:</h3>
No diretório home, abra o editor Vi: vi meu_arquivo.txt
Insira algum texto (por exemplo, "Testando uma estrutura de laço").
Salve e saia do Vi (:wq).

<h3>Execute o script:</h3>
Salve o script Bash fornecido em um arquivo (por exemplo, modificador.sh).
Torne o script executável: chmod +x modificador.sh
Execute o script, fornecendo o caminho do diretório e o nome do arquivo: ./modificador.sh /home/seu_usuario meu_arquivo.txt

<h2>Explicação do script</h2>
<strong>1º Solicita o diretório:</strong> O script pede ao usuário que insira o caminho do diretório onde o arquivo está localizado.
<strong>2º Verifica o diretório: </strong>O script verifica se o diretório fornecido existe.
<strong>3º Solicita o nome do arquivo:</strong> Se o diretório existir, o script pede o nome do arquivo.
<strong>4º Verifica o arquivo:</strong> O script verifica se o arquivo existe e se é um arquivo de texto (.txt).
<strong>5º Exibe o conteúdo original:</strong> Se o arquivo existir e for um arquivo de texto, o script exibe o conteúdo original do arquivo.
<strong>6º Modifica o conteúdo:</strong> O script lê o arquivo linha por linha, separa cada linha em palavras e adiciona "X" no início e no final de cada palavra.
<strong>7º Exibe o conteúdo modificado:</strong> O script exibe o conteúdo modificado.

<h2>Exemplo</h2>
<h3>Conteúdo original do arquivo :</h3>
![Captura de tela 2025-02-21 215543](https://github.com/user-attachments/assets/947f32bd-c5fe-4c9d-924e-c170670ae4a8)![imagem_2025-02-21_215842713](https://github.com/user-attachments/assets/8fab8c20-0431-4622-b044-f47f4d648657)

<h3>Conteúdo modificado:</h3>
![Captura de tela 2025-02-21 215623](https://github.com/user-attachments/assets/700ba611-5973-40cc-8810-4b0d2fc05985)

Obrigado pela sua atenção!!

