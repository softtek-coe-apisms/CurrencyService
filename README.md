CurrencyService

Developed in ASP.NET Core.

Is a currency converter, updated daily.
Returns an amount in the desired currency.

The request body format example:

{
  "CurrencyCode": "MXN",
  "Units": 1,
  "Nano": 0,
  "CurrencyType": "USD"
}


The response body is similar to:
0.0418532158


_________________
CurrencyService

Desarrollado en ASP:NET Core
Es un convertor de moneda, actualizado diariamente.
Regresa un cantidad en la moneda deseada.

Recibe un body en formato json:
{
  "CurrencyCode": "MXN",
  "Units": 1,
  "Nano": 0,
  "CurrencyType": "USD"
}


El response body es similar a:
0.0418532158