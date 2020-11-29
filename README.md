# HumiditySensor - “Embedded systems”

- First week: <br> 
The first week was the introduction to embedded systems by getting acquainted with the STM32 boards on which the whole project was based. This week's activities were divided into two parts: in the first part of the day before the break there were several presentations that would help us to make the main project we chose in the second week, and in the second part we tried and saw the application of the previously presented material. <br> 
I worked with the STM32L100C board in the first week. I learned solidly how to use Atollic TrueSTUDIO, STM32CubeMX and TouchGFX, which I initially had difficulty with.
I also had the opportunity during the whole internship to keep my plate and try to learn additional things after the working day. <br> 
At the end of the first week we had project proposals from the mentor and we could think for a few days on what topic we would like to work on.


- Second week: <br> 
At the beginning of the second week we divided into groups and chose topics. I was working with another colleague on a team on "Automated Smart Irrigation System".
We first made the project on the STM32L100C board, but since this board did not have a built-in screen we switched to the STM32f769i Discovery in order for the final 
presentation to be better. In the main program I enabled to read the values ​​given by the sensor and I also performed the mapping of the same.  <br> 
We set a condition for soil moisture in order to prevent the plants from drying out, and we prevented that with a special pump that irrigated the 
soil if the condition is met, ie the humidity is lower than we want. Since every plant needs a different level of soil moisture, we set an interrupt which, 
by clicking on the button that is built into the plate, increases the limit by 5% until we reach 100% and then returns to the initial set value.


- Third week: <br> 
In the third week we made a display of the change in humidity on the screen from the board itself in the form of a graph that when it reached the end of 
the screen we took the second part of the values and put them at the beginning so that the measurements could continue and be seen. part of the previous ones. <br> 
During this week we have created special conditions with which appropriate messages appear on the screen. For example a message if the sensor is not in the 
ground or the sensor is not well connected and so on.


- Fourth week: <br> 
Last week we tested the project and saw what little things we could add to make it look better (such as changing the colors on the screen).  <br> 
Once we were sure that everything was working as we wanted we had to make a presentation of what we had made.
 <br> 

 => Gabriel Dimitrievski
