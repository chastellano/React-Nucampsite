# React Nucampsite

This is a responsive, single page React application for a campground website. The app’s principal resources are kept on an external server, it uses Redux for managing the local store. When data is received from the user, actions are dispatched that make calls to the server using the Fetch API. These actions perform CRUD operations, update state data, and provide error handling. Asynchronous calls to the database are handled using Redux Thunk.

![screencapture-localhost-3000-directory-0-2021-06-15-16_44_09](https://user-images.githubusercontent.com/73765884/122154360-d8727b00-ce32-11eb-89a5-e246e6871ff4.png)
<br><br>

The Contact and CampsiteInfo components have controlled forms with client-side data format validation that is tracked by the Redux store. The Log In form is a basic uncontrolled form tracked by the DOM using refs.

![screencapture-localhost-3000-contactus-2021-06-15-22_48_11](https://user-images.githubusercontent.com/73765884/122154705-8bdb6f80-ce33-11eb-84fe-cbac038542a6.png)
<br><br>

React transitions are used for rendering various presentational components, including loading animations for asynchronous calls to the database to let the user know when resources are loading.

![screencapture-localhost-3000-home-2021-06-15-22_46_51](https://user-images.githubusercontent.com/73765884/122154833-ccd38400-ce33-11eb-9b55-55c3409f1a92.png)
![screencapture-localhost-3000-home-2021-06-15-22_46_36](https://user-images.githubusercontent.com/73765884/122154947-fee4e600-ce33-11eb-8ada-2fca4884dfce.png)

