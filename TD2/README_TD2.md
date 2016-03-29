LE DEMANDE:
---------------
Ecrivez une grammaire en PEG.js pour valider si un numero de carte de credit est vadid ou non

LA SOLUTION:
---------------
Merge din 4 in 4 si verifica daca exista caracterul "-" si le numara punandu-le intr-o variabila.
Numara caracterele din sir si verifica daca este egal cu numarul de caractere care ar trebui sa fie intr-un numar de creditcard

EXEMPLE DE FONCTIONNEMENT CORRECT:
---------------
1234-4564-3453-3432
3456-3565-3565-5643
1432-3456-2343-4533

VERIFICATION DU FONCTIONNEMENT CORRECT:
---------------
1.Intram pe siteul http://pegjs.org/online
2.Se introduce continutul fisierului "TD2.md" in editor.
3.Se introduce in input stringul pe care dorim sa-l validam (ex. "1234-1234-1234-1234")
4.In sectiunea "Output" va fi afisata validarea stringului astfel:
true - daca stringul dat reprezinta un numar de card de credit valid
false - daca stringul dat nu reprezinta un numar de card de credit valid

