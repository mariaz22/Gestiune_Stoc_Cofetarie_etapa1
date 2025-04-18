# Gestiune_Stoc_Cofetarie_etapa1

## Lista de actiuni ale aplicatiei:
    1.recomandare produse pentru client (meniu client)

    2.verificare daca se poate prepara un produs - daca are toate ingredientele in stoc (meniu organizator → stoc produs)

    3.cauta produse care contin un ingredient dat (meniu organizator → stoc produs)

    4.afisaza produsele sortate dupa calorii (meniu organizator → stoc produs)

    5.verifica daca exista produse sau ingrediente expirate (meniu organizator → stoc produs)

    6.verifica daca stocul este critic si genereaza alerte de stoc (meniu organizator → stoc produs)

    7.afisare cereri aprovizionare in functie de prag (meniu organizator → stoc produs)

    8.adaugare puncte de fidelitate pentru un client (meniu organizator → editare client)

    9.afisare clienti fideli (peste un prag de puncte de fidelitate dat  (meniu organizator → editare client)

    10.afisaza comenzile in functie de status (meniu organizator → editare comenzi)

    11.modifica statusul unei comenzi (meniu organizator → editare comenzi)

    12.calculeaza totalul unei comenzi (meniu organizator → editare comenzi)

    13.afisaza comenzile unui anumit client (meniu organizator → editare clienti)

    14.vizualizare istoric comenzi pentru client

    15.vizualizare puncte de fidelitate pentru client

## Colectii de date:
  -de exemplu in main am folosit liste pentru a stoca ingredientele fiecarui produs creat, HashMap-uri pentru a stoca produsele dintr-o comanda(cantitate, produs)
  -am folosit ca colectie sortata un TreeSet pentru a stoca produsele sortate dupa numarul de calorii

## Mostenire:
  -clasele derivate Bomboana, Fursec, Patiserie si Tort din clasa de baza Produs
  -clasele derivate IngredientdeBaza si IngredientSpecial din clasa Ingredient

## Clase Service:
   ProdusService, IngredientService, ClientService, ComandaService

