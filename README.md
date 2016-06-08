# ctp403
전시에 사용될 전시물 데모

This visualization is consist of mainly two type - real-time and analysis part. Upper part is corresponding to real-time visualization which provides intuitive view to user with number of circles which is positioned at the amplitude and frequency of the music. And bottom is analysis which is represented as heat-map. Every second, the program capture the tendency of the music -this time pitch - and fill up the heat-map every second. 
I utilize the graphic library d3. Additionally, for heat-map, I make good use of http://bl.ocks.org/tjdecke/5558084. My contribution at heat-map is as following. 
* I enable to plug-in real-time data into heat-map so that it can fed data dynamically. Whereas the original heat-map is only able to use static data in *.tsv format which has to be built already before being used. 
* User could analyze overall atmosphere of music while playing music. 
* For this project, I only plug pitch but it could be potentially used for any other factors of music.

View demo at http://soyapark45.github.io/ctp403/demo.html 

![alt tag](https://cloud.githubusercontent.com/assets/3036721/15880958/1e42ff68-2d6d-11e6-9d5a-d21c0c8a1321.png)
