<h1>Modificador de Palavras em Arquivos TXT</h1>
Este script Bash modifica o conteúdo de arquivos de texto (.txt), adicionando "X" no início e no final de cada palavra.

<h2>Pré-requisitos</h2>
Distribuição Linux Conectiva 10 (ou similar)<br>
Editor de texto Vi<br>

<h2>Como usar</h2>
<h3>Crie um arquivo de texto:</h3>
° No diretório home, abra o editor Vi: vi meu_arquivo.txt<br>
° Insira algum texto (por exemplo, "Testando uma estrutura de laço").<br>
° Salve e saia do Vi (:wq).<br>

<h3>Execute o script:</h3>
° Salve o script Bash fornecido em um arquivo (por exemplo, modificador.sh).<br>
° Torne o script executável: chmod +x modificador.sh<br>
° Execute o script, fornecendo o caminho do diretório e o nome do arquivo: ./modificador.sh /home/seu_usuario meu_arquivo.txt<br>

<h2>Explicação do script</h2>
<strong>1º Solicita o diretório:</strong> O script pede ao usuário que insira o caminho do diretório onde o arquivo está localizado.<br>
<strong>2º Verifica o diretório: </strong>O script verifica se o diretório fornecido existe.<br>
<strong>3º Solicita o nome do arquivo:</strong> Se o diretório existir, o script pede o nome do arquivo.<br>
<strong>4º Verifica o arquivo:</strong> O script verifica se o arquivo existe e se é um arquivo de texto (.txt).<br>
<strong>5º Exibe o conteúdo original:</strong> Se o arquivo existir e for um arquivo de texto, o script exibe o conteúdo original do arquivo.<br>
<strong>6º Modifica o conteúdo:</strong> O script lê o arquivo linha por linha, separa cada linha em palavras e adiciona "X" no início e no final de cada palavra.<br>
<strong>7º Exibe o conteúdo modificado:</strong> O script exibe o conteúdo modificado.<br>

<h2>Exemplo</h2>
<h3>Conteúdo original do arquivo :</h3>
![Imagem do Código](https://github.com/user-attachments/assets/76832a9e-40ee-4250-95b2-fbb08c3c7f58)
![Imagem do Código](https://github.com/user-attachments/assets/47fd3cfe-6a89-471b-838c-bb872e511aa9)



<h3>Conteúdo modificado:</h3>
![Resultado do Código](https://github.com/user-attachments/assets/700ba611-5973-40cc-8810-4b0d2fc05985)

<br>Obrigado pela sua atenção!!

