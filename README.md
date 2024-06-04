In this project, let's build a **Gradient Generator** app by applying the concepts I have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/gradient-generator-output-v0.gif" alt="gradient-generator" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>



- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>


The app have the following functionalities

- Initially, the selected gradient direction should be the first value in the given `gradientDirectionsList`
- The initial values for the HTML input elements with type color should be **#8ae323** and **#014f7b** respectively
- When the values are provided for both the input elements with type color, then provided values should be the text content for the respective paragraph elements
- When the **Generate** button is clicked after selecting the direction and picking the colors, the background of the app should have a linear gradient with the selected direction and colors provided

- The `GradientGenerator` component will consist `gradientDirectionsList`. It consists of a list of gradient directions objects with the following properties in each gradient directions object

  |    Key      | Data Type |
  | :--------:  | :-------: |
  | directionId |  String   |
  |    value    |  String   |
  | displayText |  string   |


- The HTML container element for the linear gradient values are applied should have `data-testid` as **gradientGenerator**
- When a gradient direction button is active then the button should have the CSS property opacity with the value **1**
- When a gradient direction button is inactive then the button should have the CSS property opacity with the value **0.5**



