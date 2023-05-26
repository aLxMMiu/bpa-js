# bpa-js

## Assignment details:

Fa o pagina care sa aiba un formular care sa captureze date specifice unei postari de blog: - titlu - text simplu - descriere - text multiline - imagine - data publicarii - in formatul `Published at 5:34 PM on 1st of November 2023` - continut - continut HTML

Acest formular va avea un button numit post. Cand acesta este apasat, datele vor fii adaugate intr-un array de obiejecte: [{}, {}, {}] in care fiecare obiect va fi reprezentarea unei postari:

{
title: 'Blah Blah title',
description: 'This post is about blah',
datePublished: '1914-12-20 08:30:45',
image: '',
content: '<p>Some content</p><h4>Some smaller title</4>'
}

## Totul va fi pe o singura pagina si ma astept la un layout:

{{Add new post}}

{{Menu}}

Post 1

Post 2

Post 3

## {{Pagination}}

Unde - 'Add new post' va fi un link care cand va fi apasat, va descoperi formularul pentru crearea unei noi postari. - 'Menu' va fi un meniu care sa contina - un input cu optiuni de a ordona postarile dupa: titlu sau data - ascendent si descendent - un input care sa imi permita sa caut postari (search). Acesta va trebui sa caute postari dupa: continut, titlu si descriere - un input sa imi permita sa filtrez postari: - dupa date range - Post {{n}} va fi un titlu, data publicarii, imagine, descriere si 4 butoane: - 'View post': - care sa ascunda toate elementele din pagina si sa afiseze doar postarea cu: title, datePublished, image, content - va trebui sa adaugi un link la inceputul paginii 'Go back' care sa permita sa te duci inapoi la pagina de listare. - In josul paginii, dupa postare, comentariile postarii for trebui afisate cu un formular la sfarsit care sa permita adaugarea a noi comentarii - 'Edit' - care sa permita sa re-afisez formularul doar ca va avea toate inputurile fill-uite cu detaliile postarii si button-ul va fi 'Save Post' in loc the 'Add new post'. Cand va fi salvata, postarea va trebui sa ramana in aceasi pozitie in pagina cu detaliile actualizate - 'Remove' - care sa permita sa stergem postarea - 'Like' - care sa permita sa dai like la postare, ca tot iti place tie - Additional, inca un link, '5 comments' (5 sa fie numarul exact de comentarii la postare), care va duce catre postare (adica 'View post') dar cand postarea este incarcata sa scrolleze catre inceputul comentariilor - 'Pagination' - efective paginare in stilul: '< 1 2 3 >' care sa permita navigarea intre pagini. Fiecare pagina sa afiseze un numar maxim de 3 postari

Esti liber sa utilizezi packete NPM (Node Package Manager) ca sa te ajute cu cele de mai sus, dar incearca cat de cat, sa nu utilizezi un framework gen react, vue, angular. Va trebui sa utilizezi Vanilla JavaScript care efectiv a barebone cod. Ai putea de exemplu sa instalezi un packet care sa te ajute cu in WYSIWIG editor pentru 'content' ca sa capturezi continut HMTL.

Pentru a instala node si NPM https://www.youtube.com/watch?v=ENrzD9HAZK4&ab_channel=Fireship. Feel free to follow your own tutorials.
