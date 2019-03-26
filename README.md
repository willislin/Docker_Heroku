# Docker_Heroku

## Index
* [Deploy Nginx in Heroku](#Nginx)
* [Nginx_Flask](#Nginx_Flask)
* [Caddy](#Caddy)
* [Caddy_Flask](#Caddy_Flask)




## Deploy Nginx in Heroku<a name="Nginx"></a>

### Deployment command
##### heroku login :
~~~
heroku login
~~~

##### heroku container login :  
~~~
heroku container:login
~~~

##### push web:  
~~~
heroku container:push web --app <app_name>
~~~

##### release web:  
~~~
heroku container:release web --app <app_name>
~~~

##### open app :  
~~~
heroku open -app <app_name>
~~~



## Nginx_Flask <a name="Nginx_Flask"></a>
## Caddy <a name="Caddy"></a>
## Caddy_Flask <a name="Caddy_Flask"></a>