# Steganography-on-random-Image
This program creates a random color noise and then appends information and then gives an encoded image
## What is Steganography?
***The act of taking the storing image data in an image.***
## **So how is the text stored into an image?**
First of all we can consider the image to be set of values in the format or **R,G **and **B**. 
This means we can change these numbers with our whatever we need!
In this project, I have used the **XOR** property.
> XOR property says that **If a is xored with b to attain c then you can only obtain a if you xor c with b.
This means if I xor the ASCII of characters with the RGB values then it will create a newer RGB value.4
In the below image consider a pixel with the values of (253,36,28) for (R,G,B) and we the text "hel". 
![image](https://user-images.githubusercontent.com/99396752/182440681-4a0199f1-ba4e-41f3-906a-d48a5189bec7.png)
Now, take the ascii values for each alphabets and then take the xor with the respective pixel value.
Now do the reverse of it, take the original image and then use the encrypted value and xor it, you will get something like this : 
![image](https://user-images.githubusercontent.com/99396752/182442905-75efe954-91cd-4ec7-a244-b4b9662d8eb7.png)
## **Which image to choose?**
Now which image to use?
*One way is to give the user a chance to upload an image!*
But, if by mistake if someone has the same image he or she can easily find out the text inside the image!
***So, How do we solve this problem?????***
Randomnly create the image!!!
We can create a Random image as depicted below and then use it for the encoding the text into the image.
The randomly created image!!!
![random](https://user-images.githubusercontent.com/99396752/182443147-0c7f557d-bdaf-487e-a9fa-3b4929d140d3.png)
This image is a completely randomly generated and then is used to encode the text.
The encoded image looks like this!!!
![Encoded](https://user-images.githubusercontent.com/99396752/182443406-879f8c0a-8ca2-4dbe-a9ff-5ff0f9fef11e.png)
This above image is the same as the one uploaded in the repository. 
This you can download from github by cloning this repository.
## **Why using this?
This is a method of encryption which, if you don't have the original image then, the decoding of this will even make the Quatum Computers Sweat!!!
## **Outcome
From this project you will get to know about a new way of encoding a text into an image except of shifting the pixel value by 0 or 1.
