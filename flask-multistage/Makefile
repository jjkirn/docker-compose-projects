export DOCKER_BUILDKIT=1

build:
	COMPOSE_DOCKER_CLI_BUILD=1 docker-compose -f docker-compose.dev.yml build
	
dev:
	docker-compose -f docker-compose.dev.yml up
	
test:
	docker build --target test --progress=plain ./app