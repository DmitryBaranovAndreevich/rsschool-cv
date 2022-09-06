---

# **Dmitry Baranov**

---

Junior Frontend Developer

---

### **My contacts:** 
* Phone: +79618026939
* E-mail: baranow.dmitry@gmail.com
* Telegram: @dmitry_a_baranov

---

### **About Me:**
I am 35 years old. I live in the city of St. Petersburg. I work for a company providing mobile communication services.

About a year ago I became interested in programming and started learning Java. With Java, I learned the basic algorithms and data structures. A few months ago I started learning JS. I liked JS more and now I'm taking a course at RS-School.

In my free time I am actively engaged in sports (rock climbing). I like to travel. I have a big white fluffy dog at home, a Samoyed breed.

I really hope that in a year I will be able to find my first job as a Frontend developer

---

### **Code example:** 
Task from the Codewars(Snail Sort): _given an n x n array, return the array elements arranged from outermost elements to the middle element, traveling clockwise._
```
snail = function (array) {
  const result = [];

  while (array.length) {
    result.push(...array.shift());
    result.push(...array.map((el) => el.pop()));
    result.push(...(array.pop()|| []).reverse());
    result.push(...array.map((el) => el.shift()).reverse());
  }
  return result;
};

```
---

### **Courses:**

* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

---

### **Languages:**

* English - reading literature
* Russian - Native