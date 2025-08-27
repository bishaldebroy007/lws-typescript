# Lesson 2: Editor Setup & Compilation

- Let's create an HTML file (index.html) along with a <script></script> at the bottom and connect script.js as usual.
- Now, the compiler will not get the typescript file named `script.ts` I created in the same directory, since they are two different files for the compiler. However, we need to help locate the file for the compiler by
  running the following command in the terminal,
  
  ```bash
  tsc script.ts
  ```

- What it will do is it will take the code from `script.ts` and create a new file in the directory `script.js` and convert the code we wrote in TypeScript into vanilla JavaScript.
- To initiate a typescript and create a config file for typescript,
  ```bash
  tsc --init
  ```
- If I want all the JS output files to be created within a specific folder (in this case, /output and for the input folder /src) within the initial project folder,
  
  <img width="822" height="435" alt="image" src="https://github.com/user-attachments/assets/98e0bae5-c778-41f4-b40d-8eb2fdbb3456" />

- If we want to specify the path from which path, all the JS will be converted to TS, we can specify that, and at the same time, we can also specify the output file.
  
  <img width="822" height="435" alt="image" src="https://github.com/user-attachments/assets/633d1812-6551-4c02-955c-099d52ac026c" />

- After completing the step, we do not need to use `tsc <file_name>.ts` or, `tsc script.ts` command. We can just use the following command since now the config knows what to do all by itself.
  
  ```bash
  tsc
  ```

- To activate the watch mode of TypeScript (Command on terminal),
  ```bash
  tsc --w
  ``` 

  
