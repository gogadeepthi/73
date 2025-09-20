let chocolates =["Perk", "KitKat", "Munch", "Milkybar"];
let list="";
for (let chocolate of chocolates){
    list += "<li>" + chocolate + "</li>";
}
document.getElementById("chocolates").innerHTML=list;
