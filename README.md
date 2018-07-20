# For local dev

This project has a docker configuracion for Drupal 8.
Update .env file if you need, this file contains the docker basic configurations.

Then just run `docker-compose up -d`

If everything went well you're done.

URLS:
- http://drupal.docker.localhost:8000/ (Drupal site)
- http://pma.drupal.docker.localhost:8000/ (PHPMYADMIN site)
- http://kibana.php.docker.localhost:8000/ (Kibana)
- http://localhost:9200/ (Elasticsearch)