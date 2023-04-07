### Source Code

- https://github.com/kaiz16/todo-dom

### Running

Make sure you have live server extension installed in your VS Code. If not, install it from here: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

- Open the project in VS Code
- Right click on index.html and select "Open with Live Server"
- Voila! The app is running on your browser

### Max Width

The reason I am using `max-width: 700px` and `width: 100%` instead of just setting `width: 700px` is to provide a responsive design that adapts to different screen sizes.

This makes sure that the container takes up 100% of the available width on smaller screens, but does not exceed 700px on larger screens.

If you set the width directly to 700px, the container would always be 700px wide regardless of the screen size. This might look fine on larger screens but could create horizontal scrolling or visual issues on smaller devices.

By using max-width and width together, we can make the design more flexible and responsive for different screen sizes.
