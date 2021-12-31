# CSSMacros
Wish you had macros for CSS development? Say no more! By including cssmacros.js at the top of your html file, you can link css libraries like normal and use @macros in that css file to allow for dynamic CSS web development! You can use use static or dynamic mode.

## Step 1
Include "cssmacros.js" at the top of your html file.
![image](https://user-images.githubusercontent.com/68836604/147839024-1f2f6241-34ad-4d9c-8d27-b7131d3fc20d.png)

## Step 2
In a css file that is referenced as a "link" element in the "head" element of your html file, create a "macros" section as shown below.
![image](https://user-images.githubusercontent.com/68836604/147839045-5fefdaab-bfd1-422f-87d0-4bff5795e225.png)

Example of what a "link" element in the "head" element looks like.
![image](https://user-images.githubusercontent.com/68836604/147839029-5ba704e0-56ed-4940-b39a-697826d3d385.png)

## Step 3
Use a macro in one of your style properties.
![image](https://user-images.githubusercontent.com/68836604/147839055-af3384ab-6268-46e1-be02-244ac7d638ee.png)

## Step 4
After DOM and styles have loaded, call window.CSSMacroEnvironment.setMacro(key [string], value [string]) and watch the magic happen!
![image](https://user-images.githubusercontent.com/68836604/147839062-8cde2e8e-e428-4c48-bf6f-44f1abd7d649.png)

Dynamic mode adjusts the values of all elements referencing the same macro!

| Before      | After       |
| ----------- | ----------- |
| ![image](https://user-images.githubusercontent.com/68836604/147839089-e7753823-3b34-4fdb-ad87-7628030402a9.png)| ![image](https://user-images.githubusercontent.com/68836604/147839103-73cb8ad9-be5f-40e6-ba49-87598da5ecad.png)|

