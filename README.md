# Wordpress Install

## Local

```bash
$ USER_NAME=$USER USER_ID=$(id -u) docker-compose up --remove-orphans --build
```

## Installing plugins
```bash
$ docker exec --user $USER -ti icecarstenscoza_wordpress_1 wp plugin install mailchimp-for-wp jetpack imsanity the-events-calendar updraftplus --activate
```

## Resources
* [Wordpress Salt Generator](https://api.wordpress.org/secret-key/1.1/salt/)
