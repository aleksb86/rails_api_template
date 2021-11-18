docker-compose build web

docker-compose run --rm web rails new . --api --database=postgresql --skip-test --skip-keeps --skip-sprockets --skip-turbolinks

sudo chown -R $USER:$USER .