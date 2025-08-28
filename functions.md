# Lesson 6: Functions

```tsc
let myFunc: Function;

myFunc = () => {
  console.log("Hello");
}
```

>[!NOTE]
> `Function` is the type of any function that can be assigned to declare a function. Although WE cannot use `function` since it is a keyword in JS/TS.


## Parameters of Function

### Required Parameters:


<img width="595" height="281" alt="image" src="https://github.com/user-attachments/assets/f51a0f1a-30e3-49be-ad13-0fcc25ad7e21" />


### Optional Parameters:

<img width="698" height="281" alt="image" src="https://github.com/user-attachments/assets/2de55e47-ad03-40e3-b864-45224bb21105" />

Here, `c?: string` is an optional value. The value could be given as a parameter or not. Depending on the user.

### Default Parameter value:

<img width="811" height="272" alt="image" src="https://github.com/user-attachments/assets/bc4b61be-0a4a-41be-aaa8-99bd0243ab58" />

Here, both are correct in terms of default parameters, `c?: string = 'any type of string'

>[!Note]
>In case of JS, if nothing is returned, it is `undefined` (this is a value). But in the case of TS, it is `void` (it means, nothing).


## Other ways

<img width="881" height="279" alt="image" src="https://github.com/user-attachments/assets/e1640e7b-6d26-4717-80e9-2834aed55f87" />

Although it is redundant but it can also be written like this.
