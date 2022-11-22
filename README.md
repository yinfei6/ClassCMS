# classcms
The file management function module of Classcms<=3.5 has an arbitrary file upload vulnerability.
Classcms modules are downloaded through its official website. All versions of the downloaded modules of the cms are the same. Therefore, as long as the functional module is installed, this vulnerability must exist. It belongs to full version pass kill. First, look at the code
![image](https://user-images.githubusercontent.com/40231393/203228160-f274d4f4-f12d-4edd-989f-04f651b206b0.png)
![image](https://user-images.githubusercontent.com/40231393/203228194-f524b250-0046-44b0-83cd-0dd01b5b3d65.png)
It can be said that the door is open. You can upload PHP directly without any interception. And this function does not match the upload blocking of the website itself.
![image](https://user-images.githubusercontent.com/40231393/203228294-c3423b4d-6dab-4e1f-a4c7-f8b3aabcd360.png)
![image](https://user-images.githubusercontent.com/40231393/203228301-e0a17ff4-8c8c-4f80-abd6-c28840f6b4ed.png)
![image](https://user-images.githubusercontent.com/40231393/203228311-47252bba-6fd0-4266-9f5d-3d47c794bce2.png)

