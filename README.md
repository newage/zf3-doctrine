# Liberatus
PHP Microservice for validation JWT
 
## Set up
### Docker
1. Copy `docker/.env.example` to `docker/.env` file.
2. Enter `LOCAL_IP` and `PROJECT_NAME` in `docker/.env` file.
3. Run `make build`. Build composer images.
4. Run `make up`. Up & start containers.
5. Run `make init`. Install composer dependencies.
6. Connect to the project container with PHP - `make console`.
 
 ### Manual
 
