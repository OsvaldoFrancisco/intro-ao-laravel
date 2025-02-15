# Introdução ao Laravel

Laravel é um framework PHP de código aberto, moderno e elegante para desenvolvimento de aplicações web. Ele segue o padrão MVC (Model-View-Controller) e foi projetado para tornar o desenvolvimento mais produtivo, seguro e eficiente.

## Requisitos
Antes de começar a usar o Laravel, certifique-se de que seu ambiente de desenvolvimento atende aos seguintes requisitos:

- PHP >= 8.0
- Composer
- Extensões PHP necessárias: OpenSSL, PDO, Mbstring, Tokenizer, XML, Ctype, JSON
- Banco de dados compatível (MySQL, PostgreSQL, SQLite, SQL Server)

## Instalação
Para instalar o Laravel, siga os passos abaixo:

1. **Instalar o Composer** (caso ainda não tenha instalado):
   ```sh
   curl -sS https://getcomposer.org/installer | php
   mv composer.phar /usr/local/bin/composer
   ```

2. **Criar um novo projeto Laravel**:
   ```sh
   composer create-project --prefer-dist laravel/laravel meu-projeto
   ```

3. **Navegar até a pasta do projeto**:
   ```sh
   cd meu-projeto
   ```

4. **Iniciar o servidor embutido do Laravel**:
   ```sh
   php artisan serve
   ```

Agora, sua aplicação Laravel estará acessível em `http://127.0.0.1:8000/`.

## Estrutura do Projeto
A estrutura básica de um projeto Laravel inclui:

- `app/` - Contém o código-fonte da aplicação (Controllers, Models, Middleware, etc.).
- `bootstrap/` - Arquivos de inicialização do framework.
- `config/` - Arquivos de configuração.
- `database/` - Migrações, fábricas e seeds para o banco de dados.
- `public/` - Ponto de entrada da aplicação (index.php, assets públicos).
- `resources/` - Views, assets, componentes e arquivos de tradução.
- `routes/` - Definição de rotas (web.php, api.php, console.php).
- `storage/` - Arquivos gerados, cache, logs e uploads.
- `tests/` - Testes automatizados.
- `vendor/` - Pacotes instalados via Composer.

## Comandos Básicos do Artisan
Laravel possui uma ferramenta de linha de comando chamada **Artisan**. Alguns comandos úteis incluem:

- `php artisan serve` - Iniciar o servidor local.
- `php artisan migrate` - Executar migrações do banco de dados.
- `php artisan make:model NomeDoModel -m` - Criar um Model com migração.
- `php artisan make:controller NomeDoController` - Criar um Controller.
- `php artisan route:list` - Listar todas as rotas registradas.

## Lista de Livros para Ler
1. *Laravel: Up & Running* - Matt Stauffer
2. *Laravel: From Apprentice To Artisan* - Taylor Otwell
3. *Modern PHP* - Josh Lockhart
4. *PHP Objects, Patterns, and Practice* - M. Papantonio
5. *Laravel Design Patterns and Best Practices* - Kelt Dockins

## Boletins Informativos para se Manter Atualizado
1. [Laravel News](https://laravel-news.com/)
2. [PHP Weekly](https://www.phpweekly.com/)
3. [Laravel Dispatch](https://laraveldaily.com/)
4. [DevDojo Laravel Newsletter](https://devdojo.com/)
5. [Laracasts Newsletter](https://laracasts.com/)

## 10 Blogs de Engenharia da Empresa
1. [Laravel News Blog](https://laravel-news.com/)
2. [Tinkerwell Blog](https://tinkerwell.app/blog)
3. [Spatie Blog](https://spatie.be/blog)
4. [Laravel Daily](https://laraveldaily.com/)
5. [Murze Blog](https://murze.be/)
6. [Beyond Code Blog](https://beyondco.de/blog)
7. [Freek.dev](https://freek.dev/)
8. [Pest PHP Blog](https://pestphp.com/blog)
9. [PHPStan Blog](https://phpstan.org/blog)
10. [The Laravel Podcast](https://laravelpodcast.com/)

## Considerações Finais
Laravel é um framework robusto e flexível para desenvolvimento de aplicações web. Aprender e se manter atualizado com suas melhores práticas e novidades é essencial para construir aplicações escaláveis e seguras.

Para mais detalhes, consulte a [documentação oficial](https://laravel.com/docs).

---
**Informações de contato:**
📧 Email: redeao.dev@gmail.com
