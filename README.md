# hometask
// С помощью условных операторов вывести на экран длину наибольшего отрезка из трех данных

const a = 1;
const b = 2;
const c = 3;

if ((a > b) && (a > c)) {
    console.log("a");
} else if ((b > a) && (b > c)){
    console.log("b");    
} else {
    console.log("c");
}

//ниже -30: “Оставайтесь дома!”;
// от -30 до -10 включительно: “Сегодня холодно”;
// от -10 до +5 включительно: “Не холодно”;
// от +5 до +15 включительно: “Тепло”;
// от +15 до +25 включительно: “Очень тепло”;
// от +25 до +35: “Жарко”;
// выше либо равно +35: “Пекло!”

let temperature = +35;

if (temperature < (-10)) {
    console.log("Оставайтесь дома!")
} else if ((-30) <= temperature && temperature <= (-10)) {
    console.log("Сегодня холодно")
} else if (temperature > -10 && temperature <= +5) {
    console.log("Не холодно")
} else if (temperature > +5 && temperature <= +15) {
    console.log("Тепло")
}  else if (temperature > +15 && temperature <= +25) {
    console.log("Очень тепло")
} else if (temperature > +25 && temperature < +35) {
    console.log("Жарко")
} else if (temperature >= +35) {
    console.log("Пекло!")
}

const typeUser = "User";
const birthday = '01.12.1999';
const favoriteDrink = 'water';

switch (typeUser) {
    case 'manager':
        console.log(`birthday`);
        break;
    case 'user':
        console.log(`favoriteDrink`);
        break; 
    case 'admin':
        console.log(`typeUser`);
        break;
    default:
        console.log("Введите тип пользователя");
        break;   
}
