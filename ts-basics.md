# Basics of TypeScript

<img width="480" height="270" alt="image" src="https://github.com/user-attachments/assets/30bc5dbf-868f-4d80-8cd7-b2bda480a968" />

See? The code was not even executed to notice the error in the case of TS. <br />

## How is this working?

This process is called inferencing in the TS language. Since I've once assigned a string to a variable, I cannot assign an integer to the same variable. The code assumes and expects a string. <br />

But, there is a catch: this will only happen when the variable declaration and assignment happen at the same time. See the example below,

<img width="480" height="270" alt="image" src="https://github.com/user-attachments/assets/d0031c76-0b84-499a-b37c-7a472ce37a6f" />

<img width="1056" height="304" alt="image" src="https://github.com/user-attachments/assets/4301109b-7202-4a83-baf2-5561db27afe8" />

The declaration was done in the first line, but the value assigngment was done later, and it is not considered an error in TS.

## Example 1

<img width="1056" height="304" alt="image" src="https://github.com/user-attachments/assets/051c121d-b641-4008-8297-820eda4833b5" />

In this function a and b variables have type "any". So, if a user unintentionally sends a string instead of an integer, JavaScript will not create any issue about it, but TypeScript will let the programmer know that it is not the correct way. The correct way is, <br />

<img width="1057" height="341" alt="image" src="https://github.com/user-attachments/assets/448c1fb4-b659-437b-8a26-748fd49160a8" />

**This is called explecite type assignment**

## Array

 <img width="1057" height="341" alt="image" src="https://github.com/user-attachments/assets/8f81fa69-9671-4878-821b-cf31dac1bdec" />


In the case above, the integer is not pushable because the TS is expecting a string based on the available data in the array. 


<img width="652" height="312" alt="image" src="https://github.com/user-attachments/assets/5fb82176-d058-4aac-bbe7-8d91f56b84f4" />


In this case, the mixed array has three types of data. As a result, the next time any data that I want to keep in the same array has to be one of those available data types, otherwise, TS will show an error.

## Object

<img width="652" height="312" alt="image" src="https://github.com/user-attachments/assets/84b80439-8a7a-4359-b841-dad73de70482" />


In the case of objects, the object that is created, along with all the data types it contains, will act like a schema. Any data in the case of the above example, the name cannot be assigned as a number or any new key, like country, cannot be added after creating an object.
