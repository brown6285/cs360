all: download client server
download: download.cpp sample.h
	g++ -o download download.cpp
client: client.c
	gcc -o client client.c
server: server.c
	gcc -o server server.c
clean:
	rm client server

