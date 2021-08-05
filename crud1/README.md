### Após o clone do projeto:

* Instale as dependências
```shell
composer install
```

* Copie o `.env.example` para `.env`
```shell
cp .env.example .env
```

* Gere a chave de criptografia
```shell
php artisan key:generate
```
