1- the comand for lauch test
is go test

2 to lauch a test we need to be in
the main and have a module

3- test covarage 
//genera un archivo con en covarage
$ go test -coverprofile=coverage.out
// leer archivo de covarage
/ ver resumen resumen en la terminal
$ go tool cover -func=coverage.out
// o ver resumen en el navegador
// crea y lanza un html con el resumen
$ go tool cover -html=coverage.out 