# Lasso

For ropin' in rogue misconfigured AWS accounts into compliance
with AWS CIS Benchmarks.

## Local Dev
**Helpful Docker Commands**
```commandline
> docker-compose down -v
> docker-compose -f docker-compose.prod.yml up -d --build
> docker-compose -f docker-compose.prod.yml exec web python manage.py migrate --noinput
> docker-compose -f docker-compose.prod.yml exec web python manage.py collectstatic --no-input --clear
```

Should be accessible via [http://localhost:1337/](http://localhost:1337/)