# ALF
LE DEMANDE:
Ecrivez une grammaire en PEG.js pour valider si un numero de carte de credit est vadid ou non

LA SOLUTION:

Merge din 4 in 4 si verifica daca exista caracterul "-" si le numara punandu-le intr-o variabila.

Numara caracterele din sir si verifica daca este egal cu numarul de caractere care ar trebui sa fie intr-un numar de creditcard


EXEMPLE DE FONCTIONNEMENT CORRECT:

1234-4564-3453-3432
3456-3565-3565-5643
1432-3456-2343-4533


VERIFICATION DU FONCTIONNEMENT CORRECT:

1.Accesam http://pegjs.org/online
2.Copiaza textul din sursa in editorul online;
3.In sectiunea outputvor aparea valorile true si false daca creditul este valid respectiv invalid
