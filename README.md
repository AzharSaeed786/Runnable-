# Runnable-
Runnable ka istemal karke aap asynchronous tasks ko execute kar sakte hain Kotlin mein. Ye ek interface hai jo ek execute() method define karta hai jo code ko run karta hai. Isse aap background threads mein tasks ko run kar sakte hain, jisse UI thread ko block nahi hoga.
aapko koi aisa kaam karna ho jo time-consuming ho, jaise ke network request, file I/O, ya heavy computations, to aap yeh kaam background thread pe kar sakte hain, jisse app ka UI responsive rahega aur users ko lag nahi mehsoos hoga.
