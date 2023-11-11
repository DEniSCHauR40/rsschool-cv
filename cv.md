# Denis Chaur{
## Contacts
* Location: Slutsk
* Phone: +375 44 456-39-69
* Email: chaurdenis@gmail.com
* GitHub:DEniSCHauR40
_________________________________________________

## About me 
I am a person who goes towards his goal. Open for communication. Good luck everyone.

PS. Previously, our roads did not interest with programming.
____________________________________________________

## Skills
- HTML (Basic)
- CSS/SASS (Basic)
- JavaScript (Basic)
- Git (Basic)
____________________________________________________

## Code Example
```
let clientName = prompt('Введите имя клиента');
let clientSpentToday = prompt('Сколько клиент потратил сегодня?');
clientSpentToday = Number(clientSpentToday);
let clientSpentForAllTime = prompt('Сколько клиент потратил завсе время?');
clientSpentForAllTime = Number(clientSpentForAllTime);

let discount = 0;

if(!clientSpentForAllTime || !clientSpentToday) {
  alert('Сумма, которую клиент потратил за все время и которую потратил сегодня, должна быть числом!');  
} else {
  if (clientSpentForAllTime >=100 && clientSpentForAllTime < 300) {
    discount = 10;    
}else if (clientSpentForAllTime >=300 && clientSpentForAllTime < 500) {
    discount = 20;   
}else if (clientSpentForAllTime >=500) {
    discount = 30   
}

alert(`Вам предоставляется скидка в ${discount}%!`);
clientSpentToday = clientSpentToday - (clientSpentToday * discount / 100);
clientSpentForAllTime += clientSpentToday;

alert(`Спасибо ${clientName}! К оплате ${clientSpentToday}$. За все время в нашем ресторане вы потратили ${clientSpentForAllTime}`); 
}
```
## Experiance
______________________________________________________

## Education
+ University: _Polotsk State University_

## English
**A0** - **A1**
