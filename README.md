# SizeSpeedRun!

Welcome to SizeSpeedRun, a simple runner game built using the Runner Template in the Unity Editor. This game is designed purely for educational purposes, aimed at helping beginners understand the flow of game development and grasp concepts like level design.

## Features:

- **Two Levels**: SizeSpeedRun offers two levels for players to navigate through. Each level presents its own challenges and obstacles, providing an opportunity for players to enhance their skills.
  
- **Exit Button**: We've included an exit button within the game interface, allowing users to quit the game easily whenever they desire.

## How to Play:

1. **Objective**: The goal of SizeSpeedRun is to navigate through each level while avoiding obstacles and collecting coins and keys.
   
2. **Controls**: The character movement is cursor-based, meaning it will follow the position of your cursor on the screen. Direct the cursor to where you want the character to move - left or right- and the character will follow accordingly, navigating through the obstacles and pathways presented in each level.

3. **Collect Rewards**: Throughout the game, keep an eye out for coins and keys that can help you progress further or achieve a higher score.

4. **Complete Levels**: Successfully navigate through each level to progress to the next one. Be prepared for increasing difficulty as you advance!

5. **Exit Game**: When you're ready to exit the game, simply locate and click on the exit button within the game interface.

## Installation:

To play SizeSpeedRun, simply download the game files and run the executable file on your compatible device.

## Development:

If you're interested in exploring the game's development process or modifying it to suit your preferences, feel free to dive into the Unity project files provided. You can explore the scripts, assets, and configurations to understand how the game was built and make your own adjustments.

## Contribution:

While SizeSpeedRun is primarily an educational project, contributions are welcome. If you have ideas for improvements, bug fixes, or additional features, feel free to fork the repository, make your changes, and submit a pull request.

## Credits:

- **Unity Technologies**: We utilized the Unity Editor and its Runner Template as the foundation for building SizeSpeedRun.
  
- **GameChain**: Founded by [Ng Kai Zheng], GameChain is dedicated to revolutionizing the gaming industry through blockchain technology.

## License:

SizeSpeedRun is open-source software licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software for any purpose, with or without attribution. See the [LICENSE](LICENSE) file for more details.

## Contact:

If you have any questions, feedback, or inquiries regarding SizeSpeedRun, don't hesitate to reach out to us at [https://www.linkedin.com/in/kai-zheng-ng-a807b2251/] / [kaizheng01@hotmail.com].

Thank you for playing and happy running! 🏃‍♂️🎮


## Personal Usage
## WebGL Build Compression and Hosting on GitHub
When hosting a WebGL build on GitHub Pages, you may encounter issues related to build compression using gzip, resulting in errors such as **"Unable to parse /build/file.framework.js.gz!"** This typically occurs when the web server hosting the content is misconfigured to not serve the compressed files with the appropriate HTTP Response Header "Content-Encoding: gzip."

**"Unable to parse /build/file.framework.js.br!"** occurs if using **Brotli**

**Error Description:**
The error message indicates that the web browser is unable to parse the compressed file due to an incorrect configuration in the web server's response headers. When compression is enabled during the build process, files are often compressed using gzip to reduce their size and improve loading times. However, if the web server is not configured to correctly serve these compressed files, the browser cannot interpret them, resulting in parsing errors.

**Solution:**
To resolve this issue, you can disable build compression or ensure that the web server is properly configured to serve compressed files with the appropriate response headers.
