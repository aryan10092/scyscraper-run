link:https://aryan10092.github.io/scyscraper-run/
Skyscraper Run
Skyscraper Run is an exciting, fast-paced endless runner game where you control a plane navigating through towering skyscrapers. Avoid obstacles and soar through the sky while enjoying smooth CSS animations, different gameplay modes, and immersive audio.

Features
CSS Animations: Smooth transitions and animations for planes, obstacles, and background.
Multiple Modes: Choose between different game modes for variety and increased difficulty.
Audio: Dynamic sound effects and background music to enhance the gaming experience.
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/aryan10092/scyscraper-run.git
Navigate to the project directory:

bash
Copy code
cd skyscraper-run
Open index.html in your browser to start playing the game.

CSS Animations
The game leverages modern CSS animations to create smooth, fluid movements for the plane and obstacles. Some key animations include:

Plane Movement: The plane gently flaps its wings as it moves, giving it a lifelike feel.
Obstacle Movement: Skyscrapers and other obstacles slide into view with a smooth transition.
Background Animation: A scrolling background creates the illusion of high-speed flight.
Animations are handled by keyframes and transition properties in the CSS file:

css
Copy code
@keyframes planeFlap {
  0% { transform: translateY(0); }
  50% { transform: translateY(-5px); }
  100% { transform: translateY(0); }
}

.plane {
  animation: planeFlap 0.5s infinite;
}
Game Modes
Skyscraper Run offers a variety of game modes to keep the gameplay fresh and challenging:

Classic Mode: The original mode where you must avoid obstacles and fly as far as you can.
Time Trial: Race against the clock and try to reach the highest score within a set time limit.
Survival Mode: The longer you survive, the faster the game gets! Perfect for those looking for a real challenge.
Night Mode: A visually appealing night-time setting where the buildings glow against a starry sky.
Each mode has unique difficulty levels and visual effects.

Audio
The game features several audio elements to enhance your experience:

Background Music: A calming and motivating soundtrack plays during gameplay.
Sound Effects: Sounds for flapping wings, crashing, and collecting points.
Mute Option: Toggle audio on/off in the settings menu.
The audio is implemented using the HTML5 <audio> tag:

html
Copy code
<audio id="background-music" loop>
  <source src="assets/audio/background.mp3" type="audio/mp3">
</audio>
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
