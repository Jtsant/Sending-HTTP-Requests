# Sending-HTTP-Requests  
## Day 41  
Starting with a simple starting project i will be focused on sending HTTP Requests. First i will work on how to send a GET Request and replace my 'Dummy Data' with the data from an API, specifically from swapi.dev  
My App.js file then looks like this
![Screenshot_2](https://user-images.githubusercontent.com/90603989/176731401-268f442a-211b-47dd-9957-f8d9eb406e4b.png)  
## Day 42  
Today i want to add to my app async_await syntax and after that i want to handle my Loading Data States so that if something takes a bit of time to process the user can get a message or an icon that informs him that the app is loading. Lastly i want to handle any Http Errors in the case of something going wrong with the server. My app then returns the message on the screen that something wnet wrong like this ![Screenshot_1](https://user-images.githubusercontent.com/90603989/176935974-1c67d7ab-4d87-43ee-b38f-ab26aff637ee.png)  
My App.js file then looks like this after all the changes ![Screenshot_2](https://user-images.githubusercontent.com/90603989/176935966-cfc57334-98ea-4d53-aa86-9a2256bbed45.png)  
## Day 43  
In order for my app to show the data from the API every time it is loading instead of only showing when pressing the button Fetch Movies i will use the useEffect hook to handle the Requests. 
