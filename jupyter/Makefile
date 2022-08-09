clean:
		git reset --hard
		git clean -fxd

up:
	    docker-compose up --build -d
		sleep 10
		make get-logs

down:
		docker-compose down

restart:
		make down
		make up

build:
		docker-compose build

get-logs:
		docker-compose logs
