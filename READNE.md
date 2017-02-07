#Práctica 2 del laboratorio de Sistemas Distribuidos

Aplicación con arquitectura cliente-servidor generada con RPCGen que le pide al usuario dos números y regresa la suma de dichos números.

Compilar:

	$ make -f ./Makefile.suma

Correr servidor:

	$ sudo ./suma_server

Correr cliente:

	$ ./suma_client localhost <primerNumero> <segundoNumero>
