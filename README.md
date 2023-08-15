# Elastic Toggle Switch
An elegant and visually appealing toggle switch with elastic animation and dynamic lighting effects.

## Description
This repository contains HTML and CSS code for an Elastic Toggle Switch, a user interface element that provides a toggle functionality with an interactive design. The switch has a unique elastic animation when toggled, and it features dynamic lighting effects to enhance the visual experience.

## Features
* Elastic animation when toggling the switch.
* Dynamic lighting effects that respond to the switch state.
* Modern and stylish design.

## Usage
1. Clone this repository or copy the HTML and CSS code to your project.
2. Include the `style.css` file in your HTML using the `<link>` tag.
3. Add the following HTML code to your desired location:
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Elastic Toggle Switch</title>
</head>
<body>
  <div class="content">
    <input type="checkbox" id="btn">
    <label for="btn">
      <span class="thumb"></span>
    </label>
    <div class="lights">
      <span class="light-off"></span>
      <span class="light-on"></span>
    </div>
  </div>
</body>
</html>
```

## Customization
You can easily customize the appearance of the Elastic Toggle Switch by modifying the CSS variables defined in the `style.css` file. The following are some of the variables you can adjust:

* `--sz`: Controls the overall size of the toggle switch.
* `--on`: Defines the color for the "on" state.
* `--of`: Defines the color for the "off" state.
* `--sp`: Controls the speed of animations.
  
Feel free to explore the CSS code and experiment with different values to achieve the desired visual effects.

## Credits
This Elastic Toggle Switch was inspired by creative UI designs and animations found on various design platforms. The code for this toggle switch was written by [Aarzoo Islam](https://twitter.com/Aarzoo75), based on their interpretation of those design concepts.

## License
This code is provided under the MIT License.

## Preview
<img width="905" alt="Screenshot 2023-08-15 131300" src="https://github.com/Aarzoo75/Elastic-Toggle-Switch/assets/59678435/5763dfdd-9cd0-4ed8-8830-9848046f7a03">
