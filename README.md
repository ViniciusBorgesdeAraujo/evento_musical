## Requisitos

Para executar este projeto, é necessário ter as seguintes ferramentas e recursos instalados em sua máquina:

- [XAMPP](https://www.apachefriends.org/index.html): O XAMPP é um pacote que inclui o servidor web Apache, o banco de dados MySQL, o PHP e outras ferramentas, tornando-o adequado para executar aplicativos web em ambiente de desenvolvimento.

- [Composer](https://getcomposer.org/): É um gerenciador de pacotes para PHP que será usado para instalar as dependências do projeto.

- [PHP v8.1](https://www.php.net/): A versão 8.1 do PHP ou superior é necessária para executar o projeto.

- [MySQL v8.0](https://www.mysql.com/): O MySQL versão 8.0 ou superior é o banco de dados usado neste projeto.

- [Node.js v14.17.6](https://nodejs.org/): Node.js é necessário para gerenciar pacotes JavaScript e para compilar recursos front-end.

## Instruções de Instalação e Execução

Siga estas etapas para clonar, instalar e executar o projeto:

1. Clone o repositório para sua máquina local:

```sh
 git clone git@github.com:ViniciusBorgesdeAraujo/evento_musical.git
 ```

2. Acesse a pasta do projeto:

```sh
 cd evento_musical
 ```

3. Instale as dependências do projeto usando o Composer e o npm:

```sh
 composer install
 npm install
 ```

4. Inicie o XAMPP e verifique se o Apache e o MySQL estão em execução.

5. Crie um banco de dados no MySQL.

6. Execute as migrações do banco de dados:

```sh
 php artisan migrate
 ```

11. Execute o projeto:

```sh
 php artisan serve
 ```

Após seguir essas etapas, o projeto estará em execução no ambiente XAMPP. Você poderá acessá-lo em seu navegador visitando o endereço `http://localhost:8000` (ou outro endereço indicado no terminal após a execução do comando `php artisan serve`).

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
