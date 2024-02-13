# DATE



### GET.DATE()

```js
let dias = new Date().getDate();
console.log(dias)
```

Me retorna el día

#  del mes actual.

### 

### GET.DAY()

```js
let dias = new Date().getDay()
console.log(dias)
```

Me retorna el numero del día de la semana.

###

# GET.YEAR()

```js
const moonLanding = new Date();

console.log(moonLanding.getFullYear());
```

Retornar el año actual en numeros.

###

# getHours()

```js
var Xmas95 = new Date();
var hours = Xmas95.getHours();
console.log(hours);
```

Me retorna la hora actual, (no da los minutos)

###

# getMillisecond

```js
var ahora = new Date();
var milisegundos = ahora.getMilliseconds();
console.log(milisegundos);
```

me retorna los milisegundos de la hora actual
###

# getMinutes()

```js
var Xmas95 = new Date();
var minutos = Xmas95.getMinutes();
console.log(minutos); 
```

Me retorna los minutos de la hora actual.

###

# getMonth()

```js
var Navidad = new Date();
var mes = Navidad.getMonth();
console.log(mes);
```

Me retorna el mes actual en numero-1( es decir empieza por el mes 0 y termina en mes 11)

###

# getSeconds()

```js
const moonLanding = new Date();
console.log(moonLanding.getSeconds());
```

Me retorna los segundos actuales 

###

# getTime()

```js
var birthday = new Date();
var copy = new Date();
copy.setTime(birthday.getTime());
```

comparar o calcular diferencias entre diferentes momentos en el tiempo, 

###

# getTimezoneOffset()

```js
const date1 = new Date('August 19, 1975 23:15:30 GMT+07:00');
const date2 = new Date('August 19, 1975 23:15:30 GMT-02:00');
console.log(date1.getTimezoneOffset());
console.log(date1.getTimezoneOffset() === date2.getTimezoneOffset());

```

evalúa si los minutos son los mismos y me retorna la diferencia horaria entre la hora local y la hora UTC, en minutos.

###

# getUTCDate()

```js
const date1 = new Date();
console.log(date1.getUTCDate());
```

Retorna el día del mes actual

###

#  getUTCDay()

```js
const date1 = new Date();
console.log(date1.getUTCDay());
```

Retorna el dia de la semana segun los acordes internaciones.

###

# getUTCFullYear()

```js
const date1 = new Date()
console.log(date1.getUTCFullYear());
```

Me retorna el año actual

###

# getUTCHours()

```js
const date1 = new Date();
console.log(date1.getUTCHours());
```

me retorna la hora en formato UTC

### 

# getUTCMilliseconds()

```js
const exampleDate = new Date(); 
console.log(exampleDate.getUTCMilliseconds());
```

Retorna los milisegundos en formato UTC

###

# getUTCMinutes()

```JS
const date1 = new Date();
console.log(date1.getUTCMinutes())
```

Retona los minutos actuales con formato UTC

###

# getUTCMonth()

```js
const date1 = new Date();
console.log(date1.getUTCMonth());
```

Retorna el  mes actual (comenzando con le mes 0 y termina con el mes 11 ) en formato UTC

###

# getUTCSeconds()

```js
const moonLanding = new Date();
console.log(moonLanding.getUTCSeconds());
```

Retorna los segundos con formato UTC

###

# getYear()

```JS
const xmas = new Date("1995-12-25");
const year = xmas.getYear();
```

Retorna el año (no es recomendable usarlo)

###

# Date.now() 

```js
const start = Date.now();
console.log(start);
```

Imprime los milisegundos transcurridos desde un fecha dada 

###

# Date.parse()

```js
const timestamp = Date.parse();
console.log(timestamp);
```

Retorna y analiza una cadena de fecha y hora y devuelve el número de milisegundos transcurridos

###

# setDate()

```js
const date = new Date(); 
console.log(date); 
date.setDate(15); 
console.log(date);
```

establece el día del mes de un objeto `Date`, de acuerdo con la hora local. Toma un argumento numérico que representa el día del mes y actualiza el objeto `Date` para reflejar ese cambio.

###

# setFullYear()

```js
const event = new Date();
event.setFullYear();
```

Se usa para cambiar una fecha de un evento

###

# setHours()
