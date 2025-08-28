# Lesson 12: Interfaces

- Interfaces is like a structure in TS.


## Examples 1

### General Way of doing it:


<img width="736" height="302" alt="image" src="https://github.com/user-attachments/assets/5a2d1cf9-d1e1-4710-8dc3-3255c9bc8f26" />


### Using Interfaces:


<img width="554" height="420" alt="image" src="https://github.com/user-attachments/assets/c06d4b8b-1939-452f-b8a0-fe639202d415" />


## Example 2

<img width="584" height="337" alt="image" src="https://github.com/user-attachments/assets/967c3dac-5bf7-423a-8d6f-c0d92ced6947" />

Here, the `threeDoptions` object has 3 items within the object and when it is passed as a parameter in `drawRectangle()`, TS will not show any error at all. 
But if any item is not assigned for insrance, `height` was not declared inside the function initially so unless the function, `drawRectangle()` recieves it as an object it will not expect the new item. <br />


## Example 3

### New instance:

<img width="422" height="293" alt="image" src="https://github.com/user-attachments/assets/fb7dcb17-422c-4023-a0e7-9400c2515fd2" />

After importing `isPlayer` we will be able to see an error. Because, in class it cannot access anything `private`. However, it can access, `public` or `readonly`. <br />
So, so solve the issue we have to replace `private` with `public` or `readonly` (This is one of the ways!). 

<img width="847" height="473" alt="image" src="https://github.com/user-attachments/assets/c5183dee-794a-4cad-9682-756245cd7ea1" />

Now, lets assign the type of "sakib" in `script.ts` file,

<img width="751" height="436" alt="image" src="https://github.com/user-attachments/assets/7bf83127-4da9-44b5-aa29-f6c23747e506" />


### If we want to impliment with `private`

Let's say, the age is private,

```TypeScript
private age: number;
```
All we can do is add another function let's say it's called, `getApp()`,

```TypeScript
getApp() {
  return this.age;
}
```

<img width="822" height="578" alt="image" src="https://github.com/user-attachments/assets/ff4e28d5-2c08-4996-8201-387736ba8eee" />


<img width="439" height="294" alt="image" src="https://github.com/user-attachments/assets/f9a6cc20-300d-400e-ab84-7dc139e0293a" />



## Watch the YouTube video if needed (Recommended)

- [Interfaces - YouTube](https://youtu.be/VqJ6Bjvq1GA?si=4_qOevWpIIarWurc)




