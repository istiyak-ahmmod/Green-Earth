 

---
#### 7) Create a README file to answer the following question-


#### 1) What is the difference between var, let, and const?
Answer : var : পুরনো (আগে থেকে ব্যবহৃত হয়)। একই নামের variable একাধিকবার declare করা যায় । Function scope বা global scope এ কাজ করে। Hoisting হয় (উপরে উঠে যায়), মানে declare এর আগেও ব্যবহার করলে undefined দেখায়। 

let : নতুন ES6 এ এসেছে। এটা block scope (মানে { } এর ভেতরে কাজ করে)। একই নাম দিয়ে আবার redeclare করা যায় না, তবে value change করা যায়।

const : এটাও ES6 থেকে এসেছে। Block scope এ কাজ করে।
একবার value assign করলে সেটা আর change করা যায় না।

#### 2) What is the difference between map(), forEach(), and filter()? 
Answer : map(), forEach() আর filter() array এর উপর loop চালানোর জন্য ব্যবহার হয়। তবে কাজ আলাদা:

map() : প্রতিটি item এর উপর কাজ করে এবং কাজের ফলাফল নিয়ে একটি নতুন array return করে।

forEach() : শুধু array এর প্রতিটি item এর উপর loop চালায়। নতুন কোনো array return করে না।

filter() : শর্ত চেক করে, যে item গুলো শর্ত পূরণ করে সেগুলো নিয়ে একটি নতুন array return করে।
#### 3) What are arrow functions in ES6?
Answer : Arrow function হলো ES6 এ আসা নতুন ফাংশন লেখার শর্টকাট। এতে function কীওয়ার্ড লিখতে হয় না, শুধু => ব্যবহার করে ফাংশন লেখা হয়। কোড ছোট ও clean হয়।
#### 4) How does destructuring assignment work in ES6?
Answer : Destructuring assignment হলো ES6 এর একটি ফিচার। এর মাধ্যমে array বা object থেকে value আলাদা করে সহজে variable এ নিতে পারি।
Array destructuring: 

const numbers = [15, 25, 30];
const [a, b, c] = numbers;  
a = 15, b = 25, c = 30

Object destructuring:

const user = { name: "istiyak", age: 20 };
const { name, age } = user;  
name = "istiyak", age = 20
#### 5) Explain template literals in ES6. How are they different from string concatenation?

Answer : Template literals হলো ES6 এর নতুন পদ্ধতি string তৈরি করার জন্য। এতে backtick ‌‌‌‌‌‌‌ব্যবহার হয় এবং variable বা expression সরাসরি ${} এর ভিতরে বসানো যায়।

String concatenation এ অনেক + ব্যবহার করে করতে হয় ।


