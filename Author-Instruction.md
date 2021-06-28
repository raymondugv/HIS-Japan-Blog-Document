To start editing this document on your PC, please install [this](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) (if you're using VSCode) or using [this](https://stackedit.io/app#) if you're not using VSCode as your IDE.
After installing VSCode extension, please follow thest instruction below.
1. Open Extensions by clicking on the icon on your VSCode (or `Crtl+Shift+X` on Windows)
2. Type the Extension name, in this case is `Markdown All in One`.
3. Open extension setting

![image](https://user-images.githubusercontent.com/21214764/123577936-f363c880-d7fe-11eb-9984-23d5965484d9.png)

4. Open `setting.json` file by click on **Edit in settings.json** at `Narkdown > Extention > Kantex: Macros` and then pass the following code at the end of the file.
```json
"markdown.extension.preview.autoShowPreviewToSide": true,
"markdown.extension.tableFormatter.normalizeIndentation": true,
"markdown.extension.toc.updateOnSave": true,
```

5. Save and restart your VSCode by close it and open again.
---
