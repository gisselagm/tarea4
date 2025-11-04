# XML com a llenguatge de marques

En el mòdul de **Llenguatges de marques i sistemes de gestió d’informació** de 1r de DAW, XML és un dels llenguatges fonamentals.  
Ens permet descriure i intercanviar informació d’una manera **estructurada** i **llegible tant per persones com per màquines**.

---

## Característiques bàsiques d’XML

!!! note "Què és XML?"
    **XML (eXtensible Markup Language)** és un llenguatge de marques pensat per descriure dades, no per presentar-les.

    A diferència d’HTML, que es centra en la **presentació** de la informació al navegador, XML se centra en la **estructura i el significat** de les dades.

Algunes característiques importants:

- Les etiquetes són **definides per l’usuari** (no hi ha un conjunt tancat com en HTML).
- Ha de ser **ben format** (*well-formed*): etiquetes correctament tancades, jerarquia clara, etc.
- Pot seguir o no una definició d’esquema (DTD, XSD…) per ser **vàlid** (*valid*).

---

## Exemple de document XML (fragment de codi amb numeració de línies)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<cicleFormatiu nom="DAW" any="1">
  <modul codi="0483" nom="Llenguatges de marques i sistemes de gestió d’informació">
    <resultatAprenentatge codi="RA1">
      <descripcio>
        Reconeix les característiques dels llenguatges de marques analitzant i interpretant fragments de codi.
      </descripcio>
    </resultatAprenentatge>
    <resultatAprenentatge codi="RA2">
      <descripcio>
        Utilitza llenguatges de marques per a representar documents estructurats.
      </descripcio>
    </resultatAprenentatge>
  </modul>
</cicleFormatiu>
```