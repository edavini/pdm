# Il Programmatore di merda

![pdm](static/img/pdm.png)

> Blog collaborativo di programmatori scarsi
> 
> Live @ [IlProgrammatoreDiMerda.com](https://ilprogrammatoredimerda.com)


## Disclaimer

Questa è ancora una bozza nella sua forma più semplice. Ci vorrà un po' per poterlo far crescere. Sia stilisticamente, sia di contenuti. Contribuisci!

## Che cos'è?

Un blog collaborativo dedicato ai programmatori (italiani) in cui tutti possono collaborare sfruttando semplicemente il loro account `github`

### Un blog collaborativo?

In pratica ognuno può postare nuovi articoli, proporre modifiche ad articoli pre-esistenti e, dato che siamo programmatori, anche modificare il tema e/o la struttura del sito/blog.

## Come funziona?

Il blog è realizzato con Hugo.

Per poterlo eseguire in locale basta:
1. [installare hugo sul proprio computer](https://gohugo.io/getting-started/installing).
2. clonare questo repo
3. `hugo server -D`
4. navigare `localhost:1313`


### Aggiungere un post?

1. Scrivi in markdown un file `markdown` dentro alla cartella `content/posts/`. Come nome del file scegli `2021-02-20-nome-del-post.md`
2. All'inizio del file inserisci 
```
---
title: Titolo del nuovo Post
author: Il tuo bellissimo nome
summary: Una breve descrizione da far comparire nel post
---
```
3. Effettua un push sul branch `post/2021/02/a-new-awesome-post`. 
4. Crea una Pull Request

Qualcuno la validerà e la mergerà su `master`

In automatico verrà deployata su `ilprogrammatoredimerda.com/posts/2021-02-20-nome-del-post`


### Modificare il sito?

È anche lecito modificare il sito, se ti va.

1. Fai le tue cose, testalo in locale e provalo un po'. Anche da mobile.
2. Effettua un push su `feature/2021/02/a-new-awesome-feature`, con commit belli parlanti
3. Crea una Pull request. Descrivendo molto bene quello che hai fatto e come è stata fatta.
4. Verrà validata. Probabilmente ci sarà anche un minimo di discussione.
5. Mergiata su master.
6. Va live su `ilprogrammatoredimerda.com`