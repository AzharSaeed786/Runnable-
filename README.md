# Runnable-
Java me, Runnable ek interface hai jo ek eksema ki bhi void method ko represent karta hai jo ek thread me run kiya ja sakta hai. Iska istemal typically concurrency me hota hai, jahan par aapko kisi task ko alag se ek thread me run karna hota hai.

Kotlin me, aap bhi Runnable interface ka istemal kar sakte hain, lekin Kotlin ka preference hai coroutines ka istemal karna asynchrony ke liye. Lekin, agar aapko Java ke code ko Kotlin me integrate karna hai, ya phir kisi Java library ka istemal kar rahe hain jo Runnable ka istemal karta hai, to aap Runnable interface ko Kotlin me bhi use kar sakte hain.
