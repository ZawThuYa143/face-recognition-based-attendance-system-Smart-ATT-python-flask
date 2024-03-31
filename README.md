# face-recognition-based-attendance-system-Smart-ATT-python-flask
Create a face recognition attendance collecting website using python, flask and openCv

# Implementation
I.	Technologies and Databases
The following technologies that are mainly support for website implementation are used.
•	Python Flask
Flask is a powerful and flexible micro web framework for Python, ideal for both small and large web projects. It provides a straightforward way to get a web application up and running, with all the features that need to get started.
•	HTML, CSS
HTML is a markup language used to create static web pages and web applications. CSS is a style sheet language responsible for the presentation of documents written in a markup language.
•	Bootstrap
Bootstrap is a free front-end framework for faster and easier web development. Including HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins. It also gives the ability to easily create responsive designs.
•	OpenCV
The haarcascade_frontalface_default. xml is a haar cascade designed by OpenCV to detect the frontal face. This haar cascade is available on github. A Haar Cascade works by training the cascade on thousands of negative images with the positive image superimposed on it.
•	MySQL Database
MySQL, free and open-source, is a widely used relational database management system (RDBMS). MySQL is ideal for both small and large applications.
•	System Files
File system of OS is use to store images data and attendant result.
 
II.	System Design and Usages
i.	Login Page
First for all, the Login Page is the initial page for making processes and for the usage for other relative processes and functions. In this page, we can easily Login with user name and password that we already registered or if we don’t have an account, we can create an account in Register section.

 ![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/4b50c8de-0f24-4745-b8c0-a55609c04fd0)
Figure 1 : Login Page
 ![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/ec1c9a6c-c528-4c4e-96ef-00283861f6be)
Figure 2 : Register Page
 
ii.	Home Page
	In this page, we can simply choose the pages that we desire. Also, attendant taking process can easily make if the data are already inserted. Logout tab is to log out from this account.

 ![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/f10cd751-9f12-4b64-a534-869170cba824)
Figure 3 : Home Page

iii.	Student Data Page
	In this page, not only we can insert student data but also update and delete processes are also supported by this system. After inserting the new student data, the images of student face (around 10 images) will capture in order to make training and recognition processes. Then, the system will save the student image as a file with relative file name including name and roll number.

 ![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/27da3092-d6af-4c1c-ad35-afd7f230d261)

Figure 4 : Student Data Page

 ![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/76334f68-8c98-458a-8c58-54cbd470103d)

Figure 5 : New Student Data Inserting

![image(3)](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/82fafd78-c57e-4b28-826c-a3429fc8e636)

Figure 6 : Images are saving as a file with relative file name
iv.	Profile Page
	In profile page, the data of account that logged in can be check.

![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/cfa88066-1e3f-4e9d-b034-2e4c00e97e69)

Figure 7 : Profile Page
 
v.	Taking Attendant
	To collect attendant data with face recognition, we need to go to home page and click “Take Attendance” button. Then, the system will load the recognition frame and will collect the data. The collected data are stored into the Excel Sheet and also display on the web page screen as table. The Excel Sheet is transferable and can apply for further uses.

![image(4)](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/aa59e1c3-2748-4f7d-bec8-4591b94d3b14)

Figure 8 : Face Recognition Processing Frame

![Web_Photo_Editor](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/ee3d62f3-8060-484c-9cf9-2e46c2789e56)

Figure 9 : The collected data are showed

![image](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/3c9331be-1a76-48c9-ab12-2a51b81d4bfe)
 
Figure 10 : The Excel sheet are automatically created and saved

 ![image-fotor-20240331211539](https://github.com/ZawThuYa143/face-recognition-based-attendance-system-Smart-ATT-python-flask/assets/152624230/edebc1a5-1a7f-415d-88a0-8330844f190b)

Figure 11 : Data Stored for further uses

# Further Plans and Directions
	To be a better performance and get more accurancy the better quality of camera is need to use. The higher performace processer and image taking quality also can be think for better result. The system can now process for one class well. To implement higher functional website the more databases, pertation, class and accout hanling are need to be managed. In future, the system will help not only for student and teacher to make class processes but also for university or school in security cornor by connecting with various surveillance cameras.
	If you are thinking about this system to make continuous processing, use better performace processor, resolution camera, UI/UX design, more image capture for training and recognition process, and use cloud database if the system is big enough to support for relative organization.

# Conclusion
In conclusion, the adoption of a face recognition-based attendance system represents a significant leap forward in attendance management, offering faster collecting attendance records and managing data. For time saving and generate easy recoded document for further process is the fact that need todays. The developing trends of AI and web-based technologies combining is the filed that we should not miss and should make for the improvement of various progress applications.

