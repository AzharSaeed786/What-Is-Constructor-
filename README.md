# What-Is-Constructor-
Kotlin me "constructor" ek special type ka function hota hai jo class ke instance ko initialize karta hai. Ye class ke sath sath uske properties ko set karta hai jab naya instance banaya jata hai. Kotlin me, constructors ke kuch prakar hote hain:

Primary Constructor: Ye class header ke hisse me define hota hai, jisme class ke properties declare kiye jaate hain. Primary constructor properties ko initialize karne ke liye init block ka istemal kiya ja sakta hai.

Secondary Constructor: Ye class ke body me define kiya jata hai. Ye primary constructor ke sath istemal kiya ja sakta hai ya fir agar kisi special logic ya behavior ko implement karna ho.

What is InitBlock?
init block ek special jagah hai jahan aap code likhte ho jo tab chalta hai jab class ka naya object banta hai. Matlab, jab aap ek nayi class ka object banate ho, to init block ka code turant chal jaata hai.
init Block kyun Use Karte Hain?
Initialization: Object banne ke baad kuch extra setup ya initialization karna ho.
Validation: Input values ko check karna ho aur ensure karna ho ki sab kuch sahi hai.
Logging: Debugging ke liye ya phir track rakhne ke liye ki kab kaunsa object ban raha hai.
