# Metode De Optimizare și Distribuire în baza de date
TAMBook - continuarea proiect - master an 2

[Frontend](https://github.com/alexion2001/dwbi_tam-book) - React & Backend - Oracle

TAMBook este o aplicație internă care îi permite administratorului să înregistreze o comandă pe care vrea să o plaseze utilizatorul care i-a cerut aceasta ce va conține cărțile alese în cantitatea dorită. De asemenea, dintre funcționalitățile aplicației se enumeră: vizualizarea utilizatorilor, detaliilor pentru o comandă dată, vizualizarea cărților, comenzilor și a detaliilor acestora, recenziilor, adreselor, orașelor, țărilor. Mai mult, aplicația permite modificarea numelor țărilor, orașelor (în cazul în care este necesar); utilizatorul își poate modifica numele, poate modifica cantitatea cărților dintr-o comandă, poate modifica numele străzii și blocului pentru o adresă deja înregistrată, pot modifica mesajul din review și ratingul oferit. De asemenea, mai poate fi modificat prețul cărții. 

Astfel, un utilizator poate avea mai multe adrese care conțin date de livrare printre care și orașul care face parte dintr-o țară (o țară are mai multe orașe, iar un oraș poate fi inclus în mai multe adrese), iar acesta poate plasa mai multe comenzi la adrese diferite.
În ceea ce privește comanda, aceasta, inițial, se creează pentru un utilizator și adresa selectată, cu totalul pe 0, iar în timp ce sunt adăugate detaliile comenzii – cartea aleasă, cu prețul ei în momentul respectiv, cantitatea și discountul dacă este cazul – atunci totalul din comandă este actualizat pentru a corespunde cu realitatea.

Mai mult, în acest model, o carte este publicată de o singură editură, are o singură serie, o singură categorie și un singur autor,dar o serie, categorie, autor, editură pot avea mai multe cărți. Totodată, un utilizator poate scrie mai multe recenzii pentru cărțile dorite, chiar și mai multe în aceeași zi.

Aplicația are ca scop managementul unei librării online, prin gestionarea produselor și vânzărilor, dorindu-se observarea cărților care sunt cel mai bine vândute. Aplicația permite ștergerea utilizatorilor, comenzilor, detaliilor despre comandă, adreselor, țărilor, orașelor, recenziilor.

