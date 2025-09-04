importance: 4

---

# const in Großbuchstaben?

Betrachte den folgenden Code:

```js
const geburtstag = '18.04.1982';

const alter = someCode(geburtstag);
```

<<<<<<< HEAD
Hier haben wir ein konstantes Geburtsdatum `geburtstag` und das Alter `alter`, welches berechnet wird aus `geburtstag` mittels eines gewissen Codes (dieser wird der Kürze wegen  nicht angegeben und weil Details hier keine Rolle spielen).
=======
Hier haben wir eine Konstante „geburtstag” für das Datum und außerdem die Konstante „alter”.

„alter” wird aus „geburtstag” mit „someCode()” berechnet, was einen Funktionsaufruf bedeutet, den wir noch nicht erklärt haben (das werden wir aber bald tun!), aber die Details sind hier nicht wichtig. Der Punkt ist, dass „alter” irgendwie auf der Grundlage von „geburtstag” berechnet wird.
>>>>>>> d694e895efe89922a109702085b6ca1efeffea10

Wäre es richtig, für `geburtstag` Großbuchstaben zu verwenden? Für `alter`? der sogar für beide

```js
<<<<<<< HEAD
const GEBURTSTAG = '18.04.1982'; // in Großbuchstaben?

const ALTER = someCode(GEBURTSTAG); // in Großbuchstaben?
=======
const GEBURTSTAG = '18.04.1982'; // mache Geburtstag in Großbuchstaben?

const AGE = someCode(GEBURSTSTAG); // Mache Alter in Gr0ßbuchstaben?
>>>>>>> d694e895efe89922a109702085b6ca1efeffea10
```
