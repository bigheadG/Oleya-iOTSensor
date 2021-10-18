# Oleya-iOTSensor

   This OLEYA IOT App is an IoT application that allows you to monitor remote site's Sensors data
   (such as remote site's Temperature, Humidity) with real time graphical interface, 
   and also allows you to remotely control IO devices' actions. The sensor/control unit configure in Server site.
   This App doesn't include Server Configuration function. All of the device show on this App is based on Server.



## (1)Setup Network Information: Pressed [Setup Tab]

  ![ch1](https://user-images.githubusercontent.com/2010446/137754913-5ebd3fd6-dc8e-44d9-adb0-76ce936f8fb7.png)


## (2)Key in IP, PORT, USER and Password

      (2.1) Select DIO:
          Select DIO to setup

      (2.2)Fill out Network information:
          IP : test20160608.asuscomm.com
          PORT: 51100
          USER: test
          Password: 147147147147

      (2.3) Pressed: [Get Info/Sace] button
          Get Configuration Infomation from IP address based on PORT and Password

      (2.4) Select network from table for control or monitoring.
          if no folder ICON needs pressed [Get Info/Save] again.
          folder: means the network configuration data has get data from Server.
      
   
 ## (3) Pressed [Network Tab]
    After Preesed [Network Tab] will show the Server Configuartion Information(Device/Sensor)
    (3.1) Main Sennsor/Device Server (Set Top Box Network). This text based on Server information. All of the device is configure in Sever.
     
    (3.2) Master: All of data Configure in Sever site (In this App not provides configue function).
          In this example only one Server is DEFihome.
          Select [DEFihome] will extend all of sensor/control device in the table.
    
    (3.3) Selected [Light control]: [Light Control] will enter to the control/Monitoring panal page:
    
    
  ![net1](https://user-images.githubusercontent.com/2010446/137631518-9d5b0d03-51d3-4e5f-9357-71fa5006d459.png)
  
  
## (4) Lighting Control (Control/Monitoring) Page:

    (4.0) Control/Sensor(Monitoring) device:
          Upper Button is sensor/monitoring device:
            Button(Orange) means sensor in normal state or active state based on sensor type.
            Button(Red) means sensor is ON state based lon sensor type.
          
          Under the cyan line is control device:
            Device(Button) : for control remote device.
            Button(Red/Cyan) means remote device is ON/OFF state. 
   
    (4.1) Swip to change Left/Right device page. In ths example only provides one page.
    (4.2) pressed those two keys will exit this page.
    (4.3) [Video Switch]
          Set [Video Switch]] to ON state and pressed [Device Button] will show remote monitoring video based on (4.4) config.
          Switch set to OFF state: Device(Button) is control function
    (4.4)[Video config Switch]:
          Set [Video config Switch] to ON and pressed Device Button will enter to video configure page.
          
          
  ![control](https://user-images.githubusercontent.com/2010446/137633743-1367d135-95a9-487e-8009-7798a4e45c59.png)
  
  
## (5) Video Configure Page:
    (5.0) Set [Video Config Switch] to ON state then Select [Light 5] in Light Control page:
    (5.1) Enter to Light 5 control page:
    (5.2) Set [Video Switch] to ON state and Camera pickerView will show all of the remote camera on picker.
          Once Camera Selected and set [Video Switch] to OFF state. Selected camera will map to Light 5.
    [Quit] : leave the Light 5 page.
    
    [Power Button]: Control the remote device. Orange means remote device is ON state. Gray means remote device is in OFF state. 
          
    
   ![ch5](https://user-images.githubusercontent.com/2010446/137758626-3054fda9-68ed-4e6c-aaf1-f5655b4b02d6.png)
  
  
## (6) Show video on Lighting Control Page:

    (6.1) Set [Video Switch] to ON state and pressed [Light 5] button. The video will show on screen.


## (7) Setup DMU: (Digtal Measure Unit)

    (7.0) Set [Mode Switch] to DMU mode to setup network information
    (7.1) Fill out the IP, PORT, USER and Password information
          example: IP: demo1-20170608.asuscomm.com
                   PORT: 51400
                   USER: test
                   Password: 123456789111
                             123456789222
                             123456789333

    (7.2) Pressed [Get Info/Save] to save network information.
          repeat add password and pressed [Get Info/Save]. 
          After fill out the information pressed [Done] to hide keyboard.

    (7.3) Pressed [DMSensor] Tab:

    (7.4) Pressed [net button] at Top left button that will pop up network setting page.
    
    (7.5) Pressed [Select] to select device(Based on password)
    
    (7.6) Select demo1-20170608.asuscomm.com/123456789111
          Select demo1-20170608.asuscomm.com/123456789222
    
    (7.7) Pressed [Activative] button to active selected Device.
    
    (7.8) Swipe done to leave this page.

  ![ch7](https://user-images.githubusercontent.com/2010446/137748612-37c169ff-9088-47f0-9f1c-e40b95bac535.png)
 
