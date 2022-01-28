let pass = "123qwe_"
pass.length > 3 && (pass.includes('-') || pass.includes('_')) ? console.log("Пароль надёжный") : console.log("Пароль недостаточно надёжный")





let name = "Валерий"
let surname = "ПЕтелькин"
FiO1 = name + " " + surname
FiO2 = name.substr(0,1).toUpperCase() + name.substr(1).toLowerCase() + " " + surname.substr(0,1).toUpperCase() + surname.substr(1).toLowerCase()
console.log(FiO2)
FiO1 === FiO2 ? console.log("Имя осталось без изменений") : console.log("Имя было изменено")