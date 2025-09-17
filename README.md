# E-mail Class

O E-mail Class é uma aplicação web desenvolvida em Python com Django que auxilia os usuários a gerenciar seus e-mails diários de forma eficiente. Ele classifica a prioridade dos e-mails em produtivo ou improdutivo e pode gerar respostas automáticas, otimizando o trabalho do usuário.

## Funcionalidades

- **Classificação de e-mails:** O usuário fornece um e-mail (digitando ou via arquivo .TXT) e o sistema retorna sua classificação como produtivo ou improdutivo.
    
- **Gerando respostas automáticas:** Após a classificação, o sistema sugere uma resposta automática baseada no conteúdo do e-mail analisado.

## Instalação

1. Certifique-se de ter o [Python](https://www.python.org/downloads/) e o [Django](https://www.python.org/downloads/) instalados em sua máquina.

2. Clone o repositório do projeto:

    ```bash
        git clone https://github.com/Alerreandro/Projeto-Case-Pratico-AutoU.git
        cd Projeto-Case-Pratico-AutoU
    ```
3. Instale as dependências:
    
    ```bash
        pip install -r requirements.txt
    ```
4. Configure as Variáveis de Ambiente:

    * Crie um arquivo .env na raiz do projeto
    * Adicione, dentro dele, sua chave da [API do Gemini](https://aistudio.google.com/apikey)
    * Adicione a chave secreta do django
    
    ```bash 
        GEMINI_API_KEY="SUA_CHAVE_SECRETA_DA_API_AQUI"
        SECRET_KEY="SUA_CHAVE_ALEATORIA_AQUI"
    ```
5. Colete os arquivos estáticos: 
    ```bash
        python manage.py collectstatic
    ```
6. Execute as migrações:
    ```bash
        python manage.py migrate
    ```
7. Inicie o Servidor Django:

    ```bash
        python manage.py runserver
    ```
8. Acesse a aplicação no seu navegador:

    ```bash
        http://127.0.0.1:8000/
    ```
## Acesso em Nuvem
### A aplicação também está disponível no Render

👉 [Acessar a aplicação](https://projeto-case-pratico-autou-1.onrender.com/)

⚠️ O carregamento pode levar até 50 segundos, pois a hospedagem utiliza a camada gratuita (free tier).
## Tecnologias Utilizadas

 * Django: Versão 5.2.1.
 * Python: Versão 3.11.3
 * Google Gemini API
 * HTML 
 * CSS 
 * JavaScript

## Licença
Este projeto é licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
    
