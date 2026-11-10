# Enhanced DRIVECLUB Chase Camera

This mod is all about improving the sense of speed by completely reworking how the camera behaves in every situation and for every vehicle.

It took me over a year of tweaking the camera and running countless tests to get it feeling exactly the way I wanted, especially given how limited modding every camera in this game is.

Camera settings are extremely limited, and what makes it worse is that the game won't recognize any new camera behavior scripts for any camera, including this one.

The **`Other versions`** folder is basically a set of camera presets. I put it together in case you prefer the vanilla camera shake, along with camera offset for drifting or a higher FOV, so you don't have to mess with the camera settings yourself, just pick the option that works best for you.

***This mod is compatible with all platforms***.

---

> [!NOTE]
> The camera distance coordinates were also adjusted for some vehicles to better capture the driving experience. Most of the changes are pretty minor, but for certain vehicles they’re fairly significant, in order to better convey the driving feel based on their size, road visibility, and how centrifugal force comes across during drifts.

Vehicles with significant changes:

| Vehicle | Changes (y/z axes)|
|---|---|
| `Ariel Aton 500 V8` | `y: 1.161 -> 1.3161`; `z: 3.259 -> 3.6259` |
| `Caterham SP/300.R` -> `Ariel Aton 500 V` | `y: 1.641 -> 1.161`; `z: 4.955 -> 4.1259` |
| `Caterham R500 Superlight` | `y: 1.043 -> 1.3043`; `z: 2.971 -> 3.5971` |
| `Peugeot EX1 Comcept` | `y: 1.108 -> 1.3108`; `z: 3.234 -> 3.5234` |
| `Volkswagen GTI Design Vision` | `y: 1.415 -> 1.5415`; `z: 4.102 -> 4.1402` |
| `Renault Twin'Run Concept` | `y: 1.538 -> 1.6538`; `z: 4.123 -> 4.2123` |
| `Rimac Automobili Concept_One` | `y: 1.112 -> 1.2112`; `z: 3.526 -> 3.7526` |
| `Ferrari FXX K` | `z: 4.21 -> 3.997` |
| `Koenigsegg One:1` -> `Koenigsegg Agera R` | `z: 3.978 -> 3.783` |

---

### Installation:

**Drag only the **`data`** folder into your game directory `...\CUSA00093\data\cameras\vehicle\chase_cameras\include`. Even if the **`data`** folder doesn't exist there yet, the game will still recognize it.**

P.S. If you want to return to the vanilla settings of the Chase Camera later, just drag the **`data`** folder from the **`vanilla backup chase camera`** folder into the game directory.

---

### Installing Other Versions:

Each final folder has a global file `default_chase_camera_standard` that is responsible for the chase camera behavior for all cars and must be located at the path `...\CUSA00093\data\cameras\vehicle\chase_cameras\include`.

1. Select your preferred camera preset, for example: 
`...\Enhanced Chase Camera\Other versions\High FOV\Drift follow\Central offset\Vanilla camera shake`;

2. copy the `default_chase_camera_standard` file from the last folder (`Vanilla camera shake`), and paste it into the path:
`...\CUSA00093\data\cameras\vehicle\chase_cameras\include`;

3. Confirm replace the file in the destination.

---

### License:

* This mod is a derivative work that modifies existing configuration values.
* All original game assets and files are the property of their respective copyright holders (Evolution Studios / Sony Interactive Entertainment).
* My contributions (the modified parameter values and associated configuration files) are licensed under the MIT License.