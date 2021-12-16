> 1. JavaScript is
- [ ] Compiled Language
- [ ] Assembly Language
- [ ] Interpreted Language
- [ ] Advanced Language

> 2. How to convert string to number in JS?
- [ ] parseInt("10");
- [ ] Number("10");
- [ ] "10".toNumber();
- [ ] Both a & b

> 3. What will be the value of str?

```
var year = 2021; 
str = `The year of ${year}`
```
- [ ] The year of ${year}
- [ ] The year of year
- [ ] The year of 2021
- [ ] None of above

> 4. What will be the value of num?

``` 
var num = parseInt("");
```
- [ ] NaN
- [ ] ""
- [ ] undefined
- [ ] null

> 5. How to push elements in an Arrya?

- [ ] arr.add(1)
- [ ] arr.pop(1)
- [ ] arr.push(1)
- [ ] None of above

> 6. Increment Salary by 10%

``` 
var emp = {
    name: "",
    salary: 45000
}
```
- [ ] emp.salary = 45000 * 1.11;
- [ ] emp[salary] = 45000 * 10/100;
- [ ] emp.salary += (45000 * 0.1);
- [ ] emp['salary'] += 450;

> 7. Extract month from date.

``` 
var date = new Date();
```
- [ ] date.month;
- [ ] date.getmonth;
- [ ] date.getMonth();
- [ ] None of above

> 8. What will be the value of output?

``` 
var marks = 60;
var output = marks >= 40 ? "Pass" : "Re-Exam";
```
- [ ] Pass
- [ ] Re-Exam
- [ ] undefined
- [ ] None of above

> 9. Which of the following syntax is incorrect?

- [ ] 
```
if(x % 2 == 0) {
    console.log("Even");
} else {
    console.log("Odd");
}
```
- [ ] 
```
if(x % 2 == 0) {
    console.log("Even");
}
```
- [ ] 
```
if(x % 2 === 0 && x > 0) {
    console.log("Even");
} else if(x % 2 === 1) {
    console.log("Odd");
} else {
    console.log("Zero");
}
```
- [ ] 
```
if x % 2 == 0
console.log("Even");
```

> 10. Is this loop valid?

```
for(;;) {
    console.log("Hello");
}
```
- [ ] It will throw error
- [ ] No
- [ ] It is Infinite Loop
- [ ] None of above

> 11. What will be the value of output?

``` 
var strr = "12345678";
var output = strr.slice(7, 2);
```
- [ ] "34567"
- [ ] "345678"
- [ ] "234567"
- [ ] ""

> 12. What is the role of the "continue" keyword in the following piece of JavaScript code?

``` 
while (x !=0)  
{  
if(x ==1)  
continue;  
else  
       x++;  
}  
```
- [ ] The continue keyword restarts the loop
- [ ] The continue keyword skips the next iteration
- [ ] The "continue" keyword breaks out of the loop
- [ ] It is used for skipping the rest of the statements in that particular iteration

> 13. What is used for throwing custom errors?

- [ ] new Error("Custom meaage");
- [ ] throw Error("Custom meaage");
- [ ] throw new Error("Custom meaage");
- [ ] None of above

> 14. How to parse JSON data to object?

- [ ] JSON.stringify
- [ ] JSON.parse
- [ ] Json.parse
- [ ] None of above

> 15. What will be the output?
```
var p = new Promise((resolve, reject) => {
    reject(Error('It Fails!'))
})
.then(output => console.log(output))
.catch(error => console.log(error))
```

- [ ] 'Error: It Fails' with stacktrace
- [ ] UnhandledPromiseRejectionWarning
- [ ] undefined
- [ ] None of above

> 16. How to use sendViaUPI for transferFunction argument?
```
const getSalary = (empId, base, incentives, tax, transferFunction) => {
    var salary = base + incentives - tax;
    transferFunction(empId, salary);
}

const sendViaUPI = (empId, amount) => {
    const upid = getUPIDetails(empId);
    sendToEmp(upid, amount);
}
```

- [ ] getSalary(12, 15000, 65000, 12000, transferFunction);
- [ ] getSalary(12, 15000, 65000, 12000, sendViaUPI());
- [ ] getSalary(12, 15000, 65000, 12000, sendViaUPI);
- [ ] getSalary(12, 15000, 65000, 12000, sendViaUPI(12));

> 17. Can you spot the mistake?
```
const getDataFromDB = async (query, table) => {
    var res = await sendQuery(table, query);
    return res;
}

const login = (username, password) => {
    let response = await getDataFromDB('user', {
        username: username,
        password: password
    });
}

login('admin@gmail.com', 'q1w2e3');

```

- [ ] No mistake
- [ ] const getDataFromDB = (query, table) => {
- [ ] const login = async (username, password) => {
- [ ] None of above

> 18. What will be the output printed?
```
function printLog(message) {
    console.log(`[LOG] => ${message}`);
}

const executeJob(arr, operation) {
    let output = 0;
    if(arr.length > 0) {
        if(operation === "Average") {
            for(var i = 0; i < arr.length; i++) {
                output += arr[i];
            }
            printLog(`AVG => ${output / arr.length}`);
        } else {
            printLog("Operation not valid!");
        }
    } else {
        printLog("Array is empty!");
    }
}

executeJob([1, 4, 7], "Average");
```

- [ ] AVG => 4.5
- [ ] LOG => Array is empty!
- [ ] [LOG] => Operation not valid!
- [ ] [LOG] => AVG => 4

> 19. Use the filter function to get the list of add numbers from arr.
```
let arr = [3, 4, 8, 1, 7, 4, 9];
```

- [ ] arr.filter(a => { return a/2 === 1 });
- [ ] arr.filter(a => return a%2 === 1 );
- [ ] arr.filter(a => a/2 === 1 );
- [ ] arr.filter(a => a%2 === 1 );

> 20. How to use javascript to update the value of textbox to 'Welcome to JS!'
```
<input type="text" id="greeting" />
```

- [ ] document.getElementById('greeting') = 'Welcome to JS!';
- [ ] document.getElementById('greeting').value('Welcome to JS!');
- [ ] document.getElement('greeting').value = 'Welcome to JS!';
- [ ] document.getElementById('greeting').value = 'Welcome to JS!';