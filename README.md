# My Angular WYSIWYG Editor

Little app which I wrote in order to learn Angular basics. It follows Chapter 5 (Building a WYSIWYG Editor for the Desktop using Electron) of the book <a href="https://www.packtpub.com/product/angular-projects-second-edition/9781800205260" target="_blank">*Angular Projects 2nd edition*</a>.

<br>

It displays a simple rich text editor with a toolbar and main content area, which can be packed and deployed as desktop native app using Electron.

That way you can save your work to the host file system, and open local files for editing.

<br>

The instructions in the book are clear and easy to follow. However the subject matter itself is quite challenging. Angular is verbose and complex, so the learning curve is steep.

<br>

But it was fun, and I look forward to the remaining 7 chapters!

<br>

By the way, I didn't publish the project live, since it's supposed to be bundled and distributed as a native app. So if you want to give it a try, please follow the steps below:

1. Clone the repo locally, in a folder of your choice
2. Open a terminal and navigate to said folder
3. Run the following commands:


    `> npm install`

    `> npm run build:electron`

    `> npm run package`

<br>

The last two commands are defined in `package.json`, and they will produce the native app and its dependencies in the folder `dist/my-editor-current-platform/`.

Navigate to that folder, and double-click `my-editor.exe` to launch the app. You should be able to type and format content, and it will be automatically saved to disk. After you close and reopen the app, the content from last time should be loaded again.