<div style="display:inline_block">
    <img align="left" height="100" width="100" alt="Web" src="https://www.pngall.com/wp-content/uploads/4/World-Wide-Web-PNG-Image-File.png">
</div>

# Web
Conceitos e Tecnologias da web e como desenvolver aplicações.

## Introdução

> #### DEFINIÇÃO
* A Web ou a Internet é um grande conjunto de redes de computadores interconectados por todo o mundo. Através da web é possível transmitir dados e estabelecer comunicação em seus mais diversos pontos.

> #### PROTOCOLO TCP/IP
* O TCP é o protocolo de comunicação adotado pela internet. Se baseia em estabelecer uma comunicação através das camadas de rede de forma confiável, para realizar a transferência de dados. O Protocolo IP é o responsável por realizar a comunicação entre redes definindo um endereço para cada máquina dentro da rede.

> #### PORTA
* É o responsável por mapear um processo. Para acessar a um processo deve-se acessar ao número da porta na qual aquele processo esta associado.

> #### PROTOCOLO HTTP
* Usando como base o protocolo TCP/IP, o protocolo HTTP, é utilizado na obtenção de recursos através de requisições para realizar a troca de dados entre cliente e servidor.
* A comunicação é feita através de solicitações de serviços (requisições) da parte do cliente (através de uma url e um conjunto de parâmetros) para o servidor que fornece um serviço (Geralmente documentos html, css, js e outras mídias) quando solicitado (resposta). A comunicação é feita de forma individual.
* Entre suas características estão o a simplicidade de uso, sua extensabilidade o fato de não possuir estado, ou seja, não a relação entre requisições de uma mesma conexão.
* O HTTP utiliza um conjunto de métodos que difinem diferentes tipos de operações, essas operações são definidas através dos verbos HTTP. Os verbos HTTP são: Get, Post, Put, Delete, Trace, Options, Connect e Head.
* O HTTP também possui grupos de status, que trazem informações sobre a requisição solicitada.
    - 1xx = informação;
    - 2xx = Sucesso;
    - 3xx = Redirecionamento;
    - 4xx = Erro no Cliente;
    - 5xx = Erro no Servidor.

> #### SERVER SIDE E CLIENT SIDE
* As aplicações server side são aplicações em que tanto os dados como o conteúdo, são gerados e gerenciados por um servidor.
* As aplicações client side ou aplicações front-end são aquelas em que a parte de conteúdo visual é gerado dinâmicamente através de SPAs (single page aplications) utilizando o javascript e o servidor atua apenas fornecendo serviços web (que retornam dados), geralmente em formato JSON.