# VencordCompanion

Vencord Companion is a vscode extension to test Vencord patches & webpack finds right from the comfort of your IDE.

- Adds "Test Find" on any webpack finds that will test whether your filter finds exactly one module (and not more or none)
- Adds "Test Patch" on any patches you define in definePlugin() that will test that your find is unique and your match and replace works and compiles correctly

To use it you also need to compile Vencord with DEV (aka `pnpm build --watch` or `pnpm buildWeb --watch`) and enable the  "DevCompanion" plugin. Then just start Discord!

# Installation 

[Download on the vscode marketplace](https://marketplace.visualstudio.com/items?itemName=Vendicated.vencord-companion)

If you wish to build your own VXIF file:

1. Install vsce from npm. Requires npm and the npm packages `esbuild` and `typescript`.

`npm install -g @vscode/vsce`

2. Clone the repository and enter the repository folder.

```
git clone https://github.com/Vencord/Companion
cd Companion/
```

3. Create the VXIF. It will be placed in the current directory and can be imported into VSCode using the Command Palette (Ctrl+Shift+P or F1) command `Extensions: Install from VSIX...`

`vsce package`

# Screenshots

![image](https://user-images.githubusercontent.com/45497981/224365555-60e968a1-d2d0-4aee-b29b-e5714273682c.png)

![image](https://user-images.githubusercontent.com/45497981/224377149-b1569eac-9411-4f55-849a-950ba5b06f37.png)

https://user-images.githubusercontent.com/45497981/224446924-6e272d78-2c30-41a2-a41e-f71286b5f220.mp4

