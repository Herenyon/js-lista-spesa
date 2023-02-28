creo un array con all'interno la lista della spesa

inizializzo con un let la variabile i = 0 per utilizzarla come contatore all'interno del ciclo while

creo un const lista che mi prenda dall'html l'elemento con l'id chiamato lista

comincio con il while(i < listaSpesa.lenght){} così da potermi fermare quando i ha raggiunto il numero di lista.length

all'interno del while inserisco un console.log(lista[i]), per stamapare in console il contenuto dei vari indici contenuti nell'array lista

un const chiamato prodotto = document.createElement('li'), questo e le tre righe sotto servono per scrivere nell'html una lista con il contenuto dell'array lista
poi con prodotto.append(listaSpesa[i]),
lista.append(prodotto),

e infine dopo che tutto è stato letto insterisco i++ così da incrementare i di 1 ogni ciclo fino a che non raggiunge il numero dato da lista.length


