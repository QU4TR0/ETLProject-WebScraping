# ETLProject-WebScraping

Este repositório contém um projeto de ETL (Extração, Transformação e Carga) baseado em Web Scraping, desenvolvido como parte da Jornada de Dados.

## Descrição

O projeto realiza a extração de dados de um site específico, transforma os dados conforme necessário e os carrega em um formato adequado para análise posterior.

## Estrutura do Repositório

- `data/`: Diretório que contém os dados extraídos e transformados.
- `src/`: Diretório com os scripts de código-fonte para extração, transformação e carga dos dados.
- `.gitignore`: Arquivo que especifica quais arquivos ou pastas devem ser ignorados pelo Git.
- `LICENSE`: Licença MIT para o projeto.
- `README.md`: Este arquivo, contendo informações sobre o projeto.
- `requirements.txt`: Lista de dependências necessárias para executar o projeto.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- Python 3.x
- As bibliotecas listadas em `requirements.txt`

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/QU4TR0/ETLProject-WebScraping.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd ETLProject-WebScraping
   ```

3. Crie um ambiente virtual (opcional, mas recomendado):

   ```bash
   python -m venv venv
   ```

4. Ative o ambiente virtual:

   - No Windows:

     ```bash
     venv\Scripts\activate
     ```

   - No Unix ou MacOS:

     ```bash
     source venv/bin/activate
     ```

5. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Execute o script principal para iniciar o processo de ETL:

   ```bash
   python src/main.py
   ```

   Certifique-se de que os scripts de extração, transformação e carga estão devidamente configurados no diretório `src/`.

2. Os dados extraídos e transformados serão armazenados no diretório `data/`.
3. Para visualização dos dados, foi criado um dashboard com a biblioteca Streamlit. Execute o dashboard com o seguinte comando:

   ```bash
   streamlit run app.py
   ```
   Certifique-se de que esteja dentro do diretório `src/dashboard`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes. 
