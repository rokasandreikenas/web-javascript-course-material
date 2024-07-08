
"JavaScript" - tai programavimo kalba, kuri leidžia tinklalapiuose įdiegti ivairų funkcionalumą. Tinklapio funkcionalumo pavyzdžiai yra tam tikru laiku atnaujinamas turinys (pvz., laikrodis, įrašai kalendoriuje), interaktyvūs žemėlapiai (pvz., "Google Maps" API), animuota 2D/3D grafika (pvz., tam tikra seka judantys paveikslėliai, internetiniai žaidimai) ir kita. Kartu su "HTML" ir "CSS",  ***"Javascript"*** yra trečiasis WEB "pyrago" sluoksnis.

![web_cake](https://images4.imagebam.com/56/f4/0d/MEUFNA3_o.png)


###  Pagrindinės Javascript koncepcijos

####  JavaScript Sintaksė

JavaScript sintaksė yra taisyklių rinkinys, apibrėžiantis tinkamai suformuotą JavaScript programą. Sintaksė apima, kaip rašome sakinius, kaip kuriame kintamuosius ir kaip naudojame įvairius operatorius bei raktinius žodžius.

- `console.log()`  naudojamas žinutės išvedimui į konsolę. 
```javascript
console.log('Hello World!') 
```
![javascript_console_log](https://images4.imagebam.com/d1/9d/0e/MEUFO9B_o.png)

- `//`  nurodo, kad šį simbolį eilutėje sekantis kodas yra komentaras ir jo kompiliuoti nereikia.
```javascript
console.log('Hello World!') //TODO: Put some meaningful text here
```
![javascript_console_log](https://images4.imagebam.com/d1/9d/0e/MEUFO9B_o.png)

- `/* */`  nurodo, jog visas tarp šių simbolių egzistuojantis kodas, yra komentaras.
```javascript
console.log('hi');
/*
	 TODO: Add more console.log('hi') statements.
	 TODO: Delete all the console.log('hi') statements before we launch the project.
*/
```

- `const name = "John"`  "**const**" nurodo,  jog apibrėžiamas kintamasis.
```javascript
const name = "John";
console.log(name); //Output: John
```
![javascript_console_log](https://images4.imagebam.com/5b/b7/fc/MEUFOBO_o.png)

---
####  JavaScript Kintamieji

JavaScript kintamieji naudojami saugoti įvairiem duomenim. Apibrėžti/deklaruoti kintamąjį galite pavartoję `var`, `let` arba `const`.

Raktinis žodis `var` buvo tradiciškai naudojamas seniau, tačiau `let` ir `const` yra dažniau naudojami šiuolaikiniame JavaScript.
```javascript
// Declaring a variable using var
var name = "John";

// Declaring a variable using let
let age = 30;

// Declaring a constant using const
const PI = 3.14;

console.log(name);  // Output: John
console.log(age);   // Output: 30
console.log(PI);    // Output: 3.14
```
---

####  JavaScript Duomenų Tipai

JavaScript turi įvairius duomenų tipus, įskaitant:

-   **Primityvūs tipai**: String, Number, Boolean, Null, Undefined, Symbol.
	- **String** - tekstinis.
	- **Number** - skaičiai.
	- **Boolean** - loginis "Taip" arba "Ne".
	- **Null** - tuščias.
	- **Undefined** - neapibrėžtas.
	- **Symbol** - tipas, leidžiantis apsibrėžti unikalią reikšmę.
-   **Referenciniai tipai**: Objektai (įskaitant masyvus, funkcijas).
	- **Masyvas** - reikšmių rinkinys.
	- **Objektas** - reikšmių ir jų pavadinimų rinkinys.
	- **Funkcija** - operacija skirta tam tikram darbui atlikti arba apskaičiuoti reikšmei.
	
```javascript
// Primitive data types
let str = "Hello";  // String
let num = 42;       // Number
let bool = true;    // Boolean
let empty = null;   // Null
let notAssigned;    // Undefined

// Reference data type
let arr = [1, 2, 3];  // Array
let obj = { name: "John", age: 30 };  // Object

console.log(typeof str);    // Output: string
console.log(typeof num);    // Output: number
console.log(typeof bool);   // Output: boolean
console.log(typeof empty);  // Output: object (special case)
console.log(typeof notAssigned);  // Output: undefined
console.log(typeof arr);    // Output: object
console.log(typeof obj);    // Output: object

```
---
####  JavaScript Kontrolės Sakiniai

Kontrolės sakiniai naudojami sprendimų priėmimui kode. `if` sakinys vykdo kodo bloką, jei nurodyta sąlyga yra teisinga. `else` sakinys vykdo kodo bloką, jei sąlyga yra neteisinga.

```javascript
let number = 10;

if (number > 4) {
  console.log("The number is greater than 4");
} else if (number < 1) {
    console.log("The number is less than 1");
} else {
	console.log("The number is 4 or less");
}

// Output: The number is greater than 4
```
---
**Lyginimui naudojami "operatoriai":**

![operands](https://images4.imagebam.com/af/70/9b/MEUFOSA_o.png)

```javascript
let number = 10;
let value = 15;

if (value >= number) {
	console.log("The value is greater or equal to the number");
} else {
	console.log("The value is less than the number");
}

// Output: The value is greater or equal to the number
```
---
**Papildomi operatoriai:**

![operands](https://images4.imagebam.com/a1/78/43/MEUFPP3_o.png)

```javascript
let number = 10;
let number2 = 20;
let value = 15;

if (value > number && value < number2) {
	console.log("The value is between 10 and 20");
} else {
	console.log("The value is not in range");
}

// Output: The number value is between 10 and 20
```
---
**Artimetiniai simboliai:**

![aritmetic_symbols](https://images4.imagebam.com/81/0f/57/MEUFPK3_o.png)

```javascript
let number = 10;
let value = 5;

if (value * 3 > 10) {
	console.log("The value is bigger than the number");
} else {
	console.log("The value is less than the number");
}

// Output: The number value is between 10 and 20
```
---

###  Papildomi resursai

1.  **W3Schools - JavaScript data types**: [JS Data Types](https://www.w3schools.com/js/js_datatypes.asp)

2.  **MDN Web Docs -  if...else**: ["if...else" Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

3.  **Youtube video**: [JavaScript if else (tutorial)](https://www.youtube.com/watch?v=IsG4Xd6LlsM&ab_channel=ProgrammingwithMosh)

---

###  Užduotys

1. **Užduotis: Kintamieji**

	1.1 **Tikslas**: Parašykite JavaScript programą, kuri išspausdina kintamųjų reikšmes į konsolę:
	-	Konsolėje turi būti išspausdintos **3** skirtingo tipo kintamųjų reikšmės: **String**, **Number** ir **Boolean**.
	
	1.2 **Instrukcijos**:
	- Apsibrėžkite 3 skirtingo **tipo** **kintamuosius**. (String, Number, Boolean);
	- Kiekvieną iš kintamųjų išspausdinkite į konsolę.

	1.3  **Sprendimas**:

	-   [Kintamieji](https://github.com/rokasandreikenas/web-javascript/commit/21115942d639f27308a7dc9f94c7c4e5557942ea#diff-3b8e7f46e7b263fef319f9df9ba8f96f7b6c6d934824b8aef124008d8ce9d7f3)
	---
2. **Užduotis: Kintamieji ir kontrolės sakiniai**

	2.1 **Tikslas**: Parašykite JavaScript programą, kuri įvertina ar asmuo gali balsuoti:
	-  Asmuo turi būti sulaukęs reikiamo amžiaus. (18 metų)
	- Asmuo turi būti šalies pilietis.
		- **Papildomas reikalavimas**: Asmuo šalyje turi gyventi bent 30 dienų.
	
	2.2 **Instrukcijos**:
	- Apsibrėžkite **kintamuosius** asmens amžiui, pilietybės statusui, šalyje išgyventų dienų skaičiui.
	- Panaudokite **if...else** kontrolės sakinius įvertinimui ar asmuo gali balsuoti.
	- Konsolėje išspausdinkite **if...else** rezultatą.
	
	2.3 **Sprendimas**:
	- [Kintamieji ir kontrolės sakiniai](https://github.com/rokasandreikenas/web-javascript/commit/21115942d639f27308a7dc9f94c7c4e5557942ea#diff-9431ae75f86663bb460b7e0f364ac7063ef4c0efdefb566bc002b74ce734e2f4)
	---
3. **Užduotis: Kintamieji ir kontrolės sakiniai**

	3.1 **Tikslas**: Parašykite JavaScript programą, kuri įvertintų žmogaus sveikatos riziką, atsižvelgiant į jo amžių, KMI (kūno masės indeksą) ir gyvenimo būdo veiksnius. Programa turėtų suskirstyti sveikatos riziką į skirtingus lygius ir pateikti konkrečius patarimus.
		
	3.2 **Instrukcijos**:
	- Apsibrėžkite kintamuosius `age`, `bmi` ir `smokes`.
	- Įgyvendinkite if-else logiką su keliais operatoriais, kad nustatytumėte sveikatos rizikos lygį, remdamiesi asmens amžiumi, KMI ir rūkymo statusu.
		- Maža rizika: Amžius < 30, KMI < 25 ir nerūko.
		- Vidutinė rizika: Amžius tarp 30 ir 50 (imtinai), KMI tarp 25 ir 30 (neimtinai) ir nerūko.
		- Didelė rizika: Bet kuris iš šių veiksnių yra teisingas (bet ne visi trys): Amžius > 50, KMI >= 30 arba rūko.
		- Labai didelė rizika: Visi šie veiksniai yra teisingi: Amžius > 50, KMI >= 30 ir rūko.
		- Neapibrėžta rizika: Bet kokia kita įvesčių kombinacija.
	- Savo nuožiūra pateikite patarimus, remiantis sveikatos rizikos lygiu.
	- Atspausdinkite amžių, KMI, rūkymo statusą, sveikatos rizikos lygį ir patarimus.
	
	3.3 **Sprendimas**:
	- [Kintamieji ir kontrolės sakiniai 2](https://github.com/rokasandreikenas/web-javascript/commit/21115942d639f27308a7dc9f94c7c4e5557942ea#diff-8200c3207448f2c392a548ba797366c19a86a81dbcc57ee11d22a2689974154b)