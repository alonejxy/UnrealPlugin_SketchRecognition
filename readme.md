# Installation Steps

1. Create a folder named "Plugins" in your Unreal Engine project directory.
2. Place this plugin into the "Plugins" folder.
3. Open your Unreal Engine project and enable this plugin.

# Demo

- Double-click to run the level named "Demo" in the plugin's `/Content/` directory.
- Follow the on-screen instructions in the top-left corner, press the "T" key to open the drawing board.
- Use your mouse or trackpad to sketch on the canvas, then click the "Run" button at the bottom. The recognized category will be displayed on the bottom-left, while your artwork's score for the current prompted category will be shown on the bottom-right.

# Notes

- If your project is under development, avoid using "Rebuild" in Visual Studio frequently, as rebuilding will clean the project and remove the `.dll` and `.pdb` files in `\Binaries\Win64` within the plugin, causing the editor to fail to run. Therefore, please keep a backup of the original plugin files so you can copy them over in case of issues to maintain project functionality.
- Avoid naming the test project "test" when testing this plugin, as it may cause project packaging to fail.
