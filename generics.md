# Lesson 13: Generics

- It is basically a reuseable block of code which is use in case of types.

## Examples

<img width="603" height="407" alt="image" src="https://github.com/user-attachments/assets/576ef4d8-851c-4b94-b02d-ffa9a2915599" />
<br />

In the case above, the user only knows about the type `object`, and it does not have any idea about `name` & `age` in the `addId`. As a result it is not showing any suggestions. <br />

If we wish to recieve that we can recieve it using generic. For instance, <br />

<img width="499" height="427" alt="image" src="https://github.com/user-attachments/assets/71876be4-ac5b-4c6d-9183-e0a8feb7208e" />
<br />
If I have to add a new field called, `country: 'Bangladesh'` we can simply add it to user and it will be recieved. 
<br />

<img width="491" height="352" alt="image" src="https://github.com/user-attachments/assets/2b4286d9-d8ea-4f96-9968-c0ffd76ffa47" />
<br />

**But there is an issue!!** <br />

<img width="468" height="365" alt="image" src="https://github.com/user-attachments/assets/e5162346-9b79-490b-b58f-d768ec0a1c8a" />
<br />

In the case above although it should recieve an object but it is recieving an string and it is also not showing an error. Because, it is destructuring the string and sending it normally. <br />

<img width="737" height="480" alt="image" src="https://github.com/user-attachments/assets/84a892be-61c2-4e68-b1f8-1912084b9e3b" />

<br />
If we want to provide a specific structure of the object, <br />
<img width="502" height="583" alt="image" src="https://github.com/user-attachments/assets/3df6fef0-5809-4046-b83d-abf9d37b8531" />
<br />
Here, it will only check if the required fields are given or not, `name` & `age`. That's the minimnum. however, if any extra items such as, `country` can also be added  

>[!NOTE]
>We can use anything in place of `<T>`, `T`. But it is a convention to use the type as "<T>", "T".

## Generics in Interface

<img width="359" height="405" alt="image" src="https://github.com/user-attachments/assets/cde52515-7994-4284-b276-70935fbdb709" />
<br />
Now, if we want to use, <br />
<img width="441" height="415" alt="image" src="https://github.com/user-attachments/assets/debb6a59-1c82-4a6e-90e0-009fe2ddf8e4" />

Here, as we can see the type of the `data` is an object, as a result we have placed, `APIResponse<object>`. <br />

The data will be sent as an object it will be recieved by the 'T' afterwards (This system is used because beforehand we do not know what type of data we are going to recieve). <br />


## If needed watch the Youtube Video (Recommended)

- [Generics - Youtube](/)
