# ROI_Calculator
How to add new industry and its CPL to the codes:

1. locate this block of codes, where it has a lot of `<option> `tags:

![image](https://user-images.githubusercontent.com/110692488/183141117-8226eef6-bda9-4ba1-bb3a-5867d11adc9f.png)

2. start a new line under ` <!--More options here-->`

3. copy a line of code of a `<option>` tag and paste here, then change its value and what's between the tags. for example: 

`<option value="consulting">consulting</option>`

4. locate the block of code that contains a lot of `"var CPL_XXX = XX;"` 

![image](https://user-images.githubusercontent.com/110692488/183142649-d1d7a23d-3967-4154-9846-2165b081253d.png)


5. under `//More to follow`, follow the template codes above, make a new variable that corresponding to the CPL of the industry you just added above. For example:

 `var CPL_Consulting = 100;`
 
 Its name should correspond to the industry's name. And because its javascript, there are some restrictions when naming this variable, please go through the comments in the codes, I've took a screenshot here:
 
 ![image](https://user-images.githubusercontent.com/110692488/183143413-700a342b-9e3b-4a84-ae9b-ad0d18e6e98b.png)
 
 6. Finally, locate this piece of code, and follow the instructions in the code's comment to finish the final step :
 
![image](https://user-images.githubusercontent.com/110692488/183143842-a6246769-0a14-46a3-8d8d-8a675a12f449.png)

the example code here should be : 

![image](https://user-images.githubusercontent.com/110692488/183144478-029449c8-aa29-48a2-a5d0-c92bcc514191.png)


   



