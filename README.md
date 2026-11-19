# Interactive 3D AR Alphabet Learning App

An Android augmented reality educational application built in Unity that pairs letter-tracing and alphabet cards with animated 3D models, sound playback, and interactive action controls.

## Key Features

- **Letter-Linked 3D Models:** Displays 3D objects tied to letters and vocabulary prompts (such as an airplane for **A**, basketball for **B**, cat for **C**, and dragon for **D**).
- **Interactive Actions:** Includes dedicated UI triggers (`Fly`, `Bounce`, `Move`, `Play with the Dragon`) to animate 3D models in the scene.
- **Audio & Navigation:** Provides sound playback (`Sound`) alongside a `Home` navigation button for returning to the main view.

## Project Structure

- `Assets/` — Unity scenes, 3D models, textures/materials, audio clips, UI sprites/buttons, and C# interaction scripts.
- `ProjectSettings/` — Unity build configuration, input settings, and Android target setup.
- `Packages/` — Package manifest and dependencies used by the project.

## Getting Started

1. Open the project folder in **Unity Hub** using a compatible Unity Editor version.
2. Switch the build platform to **Android** under *File -> Build Settings* (if not already configured).
3. Connect an Android device or set up your target scene, build the `.apk` / project, and test the AR view and interactive buttons.

