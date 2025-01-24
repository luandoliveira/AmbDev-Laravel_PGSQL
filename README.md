<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel

Laravel é um framework para aplicações web com uma sintaxe expressiva e elegante. Acreditamos que o desenvolvimento deve ser uma experiência agradável e criativa para ser verdadeiramente gratificante. O Laravel elimina as dificuldades do desenvolvimento ao simplificar tarefas comuns utilizadas em muitos projetos web.
Laravel é acessível, poderoso e fornece as ferramentas necessárias para aplicações grandes e robustas.

## Iniciar Projeto

A primeira etapa é cria um clone deste repositório na sua maquina ou servidor local:
```bash
git clone https://github.com/luandoliveira/AmbDev-Laravel_PGSQL.git
```

Crie uma cópia do arquivo .env.example para .env.
```bash
cp .env.example .env
```
Com o ``Docker`` e o ``Docker-compose`` instalados, basta rodar o comando:
```bash
docker compose up -d --build
```
Após o término do build da aplicação acesse o bash do container do app
```bash
docker exec -it <codigo_container> bash
```
E execute os seguintes comandos:
```bash
composer install --no-scripts # Instala as dependecias do php e laravel

php artisan key:generate # Gera a chave da aplicação
```
Feito todas as etapas, verificar no navegador o endereço de ``http://localhost:5000`` e verifique se é possível visualizar a Homepage Laravel.

![Homepage](/home.png)


## License

A framework Laravel é um software de código aberto licenciado pelo [MIT](https://opensource.org/licenses/MIT).


