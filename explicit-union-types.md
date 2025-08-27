# Lesson 4: Explicit & Union Types

## Correct way to assign value

```typescript
let a: string;
let b: number;
let c: string | number

a = "Raj";
b = 34;
c = 4;
```

## Correct way to assign an Array

If we want a string array:

```
let a: string[] = [];

a.push('Raj');
```

If we want a string or number array:

<img width="652" height="312" alt="image" src="https://github.com/user-attachments/assets/b6132521-7fe9-4040-8a5c-3206524400ba" />


## Object

<img width="652" height="312" alt="image" src="https://github.com/user-attachments/assets/06e446f2-e3e9-4c4a-b901-46f78246760f" />

**Special Note:** 

```TypeScript
let d: object;

c = [1,2,3]; //In JS array is also considered as an object
```
