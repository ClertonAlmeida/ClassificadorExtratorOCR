# Classificador e Extrator de Documentos OCR [![PLN](https://img.shields.io/badge/PLN-Expert-blue.svg)](https://github.com/seu-usuario/seu-projeto)

Este projeto visa desenvolver um robusto classificador e extrator de informações de documentos OCR (Optical Character Recognition) através da integração com a API do OpenAI. O propósito principal é identificar e classificar automaticamente o tipo de documento com base em seu conteúdo textual, além de extrair informações específicas contidas nos documentos.

## Funcionalidades

1. **Classificação de Documentos:** O sistema utiliza o modelo de linguagem natural da OpenAI para analisar o conteúdo textual dos documentos e classificá-los em categorias pré-definidas, como faturas, contratos, recibos, entre outros.

2. **Extração de Informações:** O projeto incorpora um mecanismo de extração que permite identificar e recuperar informações relevantes dos documentos. Isso inclui campos como data, valor, nome do destinatário, entre outros, dependendo do tipo de documento.

## Configuração

Antes de executar o projeto, é crucial configurar a chave de acesso à API do OpenAI. Siga as etapas abaixo:

1. Faça o download do projeto a partir do repositório no GitHub.
2. Abra o arquivo `ClassificadorDocumentoOCR.ipynb` em um ambiente de desenvolvimento Python.
3. Na célula de código marcada com o comentário "Configurar a chave de acesso OpenAI", substitua a string `"sk-xxxxxxxxxxxxxxxxxxxxx"` pela sua chave de acesso OpenAI.
4. Salve o arquivo.

## Instalação

Para garantir um ambiente adequado, certifique-se de seguir estas etapas antes de executar o projeto:

1. Verifique se o Python está instalado em sua máquina.
2. Abra o terminal ou prompt de comando.
3. Navegue até o diretório do projeto.
4. Execute o comando `pip install -r requirements.txt` para instalar as dependências necessárias.

## Uso

Para tirar proveito do classificador e extrator de informações de documentos OCR, siga as etapas abaixo:

1. Assegure-se de ter configurado corretamente a chave de acesso à API do OpenAI.
2. Abra o arquivo `ClassificadorDocumentoOCR.ipynb` em um ambiente de desenvolvimento Python.
3. Execute as células de código sequencialmente para importar as bibliotecas, definir o esquema de classificação e criar a cadeia de extração.
4. Use a função `criar_prompt(texto_ocr)` para criar um prompt com o texto OCR do documento a ser classificado.
5. Utilize a função `extrator(tipo, texto_ocr_novo)` para extrair os dados desejados do documento com base no tipo de documento fornecido.

## Contribuição

Contribuições são incentivadas e bem-vindas! Se você tiver sugestões, correções de bugs ou melhorias para o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).

Esperamos que este README seja útil para você! Se houver mais alguma dúvida, estamos à disposição para ajudar.
