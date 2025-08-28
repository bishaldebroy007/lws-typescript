# Lesson 8: Function Signatures

- A function has two things, i. Parameter & ii. Return type
- Basicaly, this two are the signature of a function.
- Let's see an example how a function signature can be made.

## Examples of Function Signature

### Example 1


<img width="541" height="114" alt="image" src="https://github.com/user-attachments/assets/9f769062-cc67-4121-b2d9-cfd98cc59308" />


### Example 2


<img width="568" height="121" alt="image" src="https://github.com/user-attachments/assets/a275eced-244b-454b-a58b-532901f60816" />


<img width="540" height="210" alt="image" src="https://github.com/user-attachments/assets/2d1c915e-5a9c-4b2c-90ec-6b98a6db3e5a" />


>[!IMPORTANT]
> 1. But, if we try to `console.log(a+b)` it will show, `void`. <br />
> 2. Here, a,b,c etc could be any valid variable but it has to have exactly same variable number as the signature.


### Example 3

<img width="781" height="430" alt="image" src="https://github.com/user-attachments/assets/40b8383a-7cee-42c9-82f5-0a71397845e4" />


To see the value from the function, we can log it,

<img width="1158" height="442" alt="image" src="https://github.com/user-attachments/assets/2e03f5cb-a940-4430-9993-f31aba5d8e30" />


Here, if any of the block, in this case `if` block or `else` block has missing `return` it will show an error. All the condition should return something, otherwise TS will show an error.


### Example 4

<img width="651" height="438" alt="image" src="https://github.com/user-attachments/assets/424de550-700a-47f7-9b90-396add98e518" />

**Correction:** <br />

In the last line of the code inside the console.log, instead of `calculations` it will be `userDetails`
