# laravel-docker-template
## usage

- Clone this repository.
```bash
git clone git@github.com:MaeK2203/laravel-docker-template.git
cd docker-laravel-template
```

- Build and run docker container from docker files.
```bash
docker-compose up -d --build
```

- Composer update.
```bash
docker-compose exec php bash -c "composer update"
```

- Using this template as other repository.
```bash
git clone --bare git@github.com:MaeK2203/laravel-docker-template.git
cd laravel-docker-template.git
git push --mirror git@github.com:xxxx/new-repository.git
cd ..
rm -rf laravel-docker-template.git
```
