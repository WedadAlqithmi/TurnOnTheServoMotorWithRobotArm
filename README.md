# TurnOnTheServoMotorWithRobotArm
for this task we learn how to assembly a robot arm and connect with the white board and UNO arduino board 


tools you will need to atchieve this task 
- white board 
- four black wires
- one yellow wire
- two red wires 
- UNO arduino 
- servo motor 
- Arduino IDE 

![بورد أبيض](https://user-images.githubusercontent.com/108210044/180245947-c0e056f3-f6eb-40b2-88c7-aed2b1ce373a.jpeg)

![قطعة الاونو](https://user-images.githubusercontent.com/108210044/180245946-bf7861c2-3842-4c27-9f25-fc5c35d262ce.jpeg)




assembly the robot arm as it shown in the image 

![تركيب الذراع](https://user-images.githubusercontent.com/108210044/180245935-5cc59c26-2715-4f3c-bc6b-bc1aabcda49a.PNG)




after that you will work with the wires in the boards 

attach the 2 black wire as it shown in the image 
make sure ton attach on in the positive and the other one at the negative 

![البورد الأبيض بعد تركيب الأسلاك السوداء للموازنة](https://user-images.githubusercontent.com/108210044/180245952-ec9f56c0-d75a-4fdf-8592-e86ebe686857.jpeg)




now you will attach one red wire at 5v port and one black wire at GND port at the UNO Arduino 
attach 2 red wires at the positive line in the white board 
and 
attach 2 black wires at the negative line in the white board 

**Note: the first red wire will be connect with the servo motor wires 
while the second red wire will be attch at the 5v port in the UNO Arduino 

do the same with the black wire but switch between the position 
so the first one will be attach in the GND port at the UNO Arduino 
and the second one will be attach to the servo motor wires 

as it shown in the image 

![قطعة الاونو بعد تركيب الاسلاك الحمرا والسودا](https://user-images.githubusercontent.com/108210044/180245944-c92cf441-aa12-400a-adc7-4c9c4225757f.jpeg)


attach the yellow 9 port at the UNO Arduino 
note you can choose any number from 2 to 12 
but make sure to change the port number in the servo sweep code 

![قطعة الاونو بعد توصيل كل الأسلاك](https://user-images.githubusercontent.com/108210044/180245941-c9cb15b4-fd88-4abc-bf4f-e8d085143b50.jpeg)



this will be the result for the UNO Arduino and the white board 
![الاونو بعد تركيب كل الأسلاك](https://user-images.githubusercontent.com/108210044/180245957-aa1a17f0-76c9-4f7c-b427-dabf18619a1b.jpeg)


![البورد الأبيض بعد تركيب الاسلاك الحمرا والسودا](https://user-images.githubusercontent.com/108210044/180245949-c5b9dcc6-cf65-4b76-aab6-1df28a98e1b5.jpeg)




Now it is time to connect the board to the Arduino IDE 

1- open Arduino IDE 
![Screenshot (638)](https://user-images.githubusercontent.com/108210044/180287392-ea517ae1-9753-47c4-ad49-ef98c9643f45.png)




2- go to the menue bar and select the following 
Tools>> Boards>> Arduino AVR  Boards>> Arduino UNO 

![Screenshot (639)](https://user-images.githubusercontent.com/108210044/180287398-f6ccd977-13c7-43bb-82c2-0cb22ff1bb7f.png)




3- now connect the arduino to your laptop 
and from the same tools bar select the correct port 
![Screenshot (640)](https://user-images.githubusercontent.com/108210044/180287401-d12952c4-f2a0-4a12-a78d-7fe85d94063b.png)



 4- install the library of servo if it is not installed yet by following the next steps 
 sketch bar>> include library>> manage library>> and search for servo then install the last version 


![Screenshot (641)](https://user-images.githubusercontent.com/108210044/180287403-fd02ffbe-e109-4849-8f76-c090b4aabfbf.png)
![Screenshot (642)](https://user-images.githubusercontent.com/108210044/180287406-e1e185d7-eb78-4df6-8f65-2c72c42fb60e.png)




5- now you can upload the servo motor code from the file bar>> examples>> servo>> sweep

![Screenshot (643)](https://user-images.githubusercontent.com/108210044/180287409-3dc7ee00-b769-46c3-af82-b1c77985fb56.png)




as i mentioned before you can change the number of the attached yellow wire 

![Screenshot (644)](https://user-images.githubusercontent.com/108210044/180287411-d6ccbc9c-d706-41a0-ab89-e91a62360ac6.png)



to change the arm movement angle you can change the initial value of pos in the for loop 

you also can chane the speed of the arm movement 

![Screenshot (645)](https://user-images.githubusercontent.com/108210044/180287414-a492602c-f9a1-497f-8091-66824476f624.png)
![Screenshot (646)](https://user-images.githubusercontent.com/108210044/180287417-71a59fbf-222f-4e6a-b995-206532cf685d.png)



this is the end result 

here is my robot arm waving and say HI 

![الذراع بالكامل](https://user-images.githubusercontent.com/108210044/180245937-21c7ad2b-659d-42fa-9125-d15ff9edd313.jpeg)


https://user-images.githubusercontent.com/108210044/180245929-cbbd9009-4e13-46dc-b3b7-3944a478c37a.mp4
