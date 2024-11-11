**comandos**
### hay que hacer este import si tienes mas de un perfile export AWS_PROFILE=personal
~~~
$ export AWS_PROFILE=personal
~~~
*Para verificar si los availability_zones devuelve una lista comprobamos de la siguiente manera para ingresar a console es necesario
hacer un apply
~~~
$ tf console
> data.aws_availability_zones.this //Esto devolvera una lista
~~~
