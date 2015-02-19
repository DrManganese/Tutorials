How to launch an ATLauncher instance with MultiMC
===

We will be using Resonant Rise 3 for this tutorial.

1) Create a MultiMC instance
---
![Setting up an instance](http://i.imgur.com/VlrwTPD.png)

Don't forget to select the correct minecraft version (1.7.10)

2) Link the ATL and MultiMC instances
---
1) Select your newly-made MultiMC instance and click _Open this instance folder in a file browser_.
![Instance folder button](http://i.imgur.com/ecFQi5C.png)

2) Delete the _minecraft_ folder.
![explorer view before link](http://i.imgur.com/Rf807jj.png)

3) Open a command terminal
* **Windows**: `WIN+R` > `Enter "cmd"` > `Click "OK"`
* **Mac**: `Navigate to"/Applications/Utilities"` > `Double-click "Terminal"`
* **Linux**: `Ctrl+Alt+T` or `Ctrl+Alt+F1`

4) Create a symbolic link to the ATLauncher instance of the pack
- In the command terminal type the following command:
  * **Windows**:
  ```Shell
  mklink \j "\path\to\MultiMC folder\instances\<instance name>\minecraft" "\path\to\ATL folder\Instances\<pack>"
  ```
  ![windows symlink](http://i.imgur.com/qK8G142.png)
  * **Linux/Mac**:
  ```Shell
  ln -s "/path/to/ATL folder/Instances/<pack>" "/path/to/MultiMC folder/instances/<instance name>/minecraft"
  ```
- You should see something similar to **this image** in your file browser:
![explorer view after link](http://i.imgur.com/oUiOniZ.png)

3) Install Forge and Liteloader
---
1) In MultiMC, select your instance and click __Edit Instance__ on the right.

![settings panel multimc](http://i.imgur.com/dWxcnti.png)

2) Click __Install Forge__ and __Install Liteloader__ and select the versions corresponding to your pack's configuration.
![buttonz](http://i.imgur.com/QtKM4rk.png)

_For Resonant Rise 3 this was `Forge 10.13.2.1291` and `Liteloader 1.7.10_04`_

4) Verify your work
---
Click the __Loader mods__ tab on the left and check if it is popuplated with mods from the _mods folder_.
![mods list](http://i.imgur.com/6FbWhsK.png)

5) Done!
---
You can now close this window and launch your instance.
![game](http://i.imgur.com/5pgJQes.jpg?1)
