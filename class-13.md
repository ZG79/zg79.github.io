## Local Storage and How To Use It On Websites

Local storage is a web browser feature that allows web developers to store data locally on the user's computer. HTTP is stateless, but if we don't want force people to sign up, then we use local storage. 

We can check using `typeof` operator to see if the browser supports local storage. 

`if (typeof(Storage) !== "undefined"){...}`

### Why would a developer use local storage for a web application?

ocal storage is a valuable tool for web developers looking to improve the functionality, performance, and user experience of their web applications. It's a good tool to store small amount of data to improve UX, though it could be potential security risk. 

### What information should not be stored in local storage?
Sensitive personal information, session data, non-encrypted data, large amounts of data, and cross-domain data should not be stored in local storage due to security and privacy concerns.

### Local storage can store what type of data? How would you convert it to that type before storing?

Only strings can be stored in the different keys. This means that when you have an object, it will not be stored the right way. But we can work around this by using the native `JSON.stringify()` and `JSON.parse()` methods. 

JSON stands for JavaScript Object Notation, which is a lightweight data format used to store and exchange data between different systems. It is often used for data communication between web servers and web applications, and has become a popular alternative to XML.

JSON is a text-based format that is easy for humans to read and write, and can be parsed and generated using JavaScript. It is based on a collection of key-value pairs, where each key is a string and each value can be a string, number, boolean, null, array, or object.

`var car = {};
car.wheels = 4;
car.doors = 2;
car.sound = 'vroom';
car.name = 'Lightning McQueen';
console.log( car );
localStorage.setItem( 'car', JSON.stringify(car) );` 


