# Blog 

## Descrição do Projeto
Este projeto é um blog dinâmico desenvolvido com Django, HTML e CSS. Permite que usuários criem, editem e excluam posts. Além disso, os visitantes podem ler os artigos e interagir através de comentários. Este blog é projetado para ser simples, mas funcional, fornecendo todas as funcionalidades essenciais de um blog moderno.

## Tecnologias Utilizadas
- **Django**: Framework de desenvolvimento web de alto nível que encoraja o desenvolvimento rápido e limpo.
- **HTML**: Utilizado para estruturar o conteúdo das páginas do blog.
- **CSS**: Usado para estilizar visualmente o blog, incluindo layout, cores e fontes.

## Funcionalidades
- **Criação de Posts**: Usuários podem criar posts que são salvos no banco de dados.
- **Edição e Exclusão de Posts**: Posts podem ser editados ou excluídos pelos seus criadores.
- **Visualização de Posts**: Visitantes podem ler os posts e navegar entre diferentes posts e categorias.
- **Comentários**: Visitantes podem deixar comentários nos posts para interagir com o conteúdo.

## Instalação e Configuração
Para configurar e rodar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/blog-django.git

2. Navegue até o diretório do projeto:
   ```bash
   cd blog-django

3. Crie um ambiente virtual:
   ```bash
   python -m venv venv

4.Ative o ambiente virtual:
   ```bash
   source venv/bin/activate  # No Windows use `venv\Scripts\activate

5. Instale as dependências:
  ```bash
   pip install -r requirements.txt

6. Realize as migrações do banco de dados:
   ```bash
   python manage.py migrate

7. Inicie o servidor de desenvolvimento:
   ```bash
   python manage.py runserver


