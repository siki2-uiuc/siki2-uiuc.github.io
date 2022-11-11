# Base HTML

This is a blank starting point upon which you can create static HTML websites.

- Create your workspace.
  - If you want to do a quick throwaway experiment, then [click here](https://gitpod.io/#https://github.com/appdev-projects/base-html) to create a Gitpod workspace based on this repository immediately.
  - Instead, if you want to save your work for posterity, then [click here](https://github.com/appdev-projects/base-html/generate) to create your own GitHub repository. This will allow you to make Git commits and push them back to GitHub for safekeeping.

    Then create a Gitpod workspace based on your own repository by typing `https://gitpod.io/#` into the address bar before your repository's URL, and pressing <kbd>return</kbd>.
- After the workspace starts up, copy-paste the following command at the `$` prompt in the Terminal pane at the bottom:

    ```bash
    ruby -run -ehttpd . -p3000
    ```

    And press <kbd>return</kbd>. This will start a web server and open a preview of your website within a pane.
  - I prefer clicking the "Open in browser" button next to the address bar of the preview pane to pop it out into its own tab. Then I close the preview pane to make more space for writing code.
  - Also, you can <kbd>Cmd</kbd>+<kbd>J</kbd> (Mac) / <kbd>Ctrl</kbd>+<kbd>J</kbd> (Windows) to toggle the Terminal pane to make more space.
- There's an existing `index.html` file whose contents — `hello, world` — should be displayed. Modify `index.html` and add other folders and files to build out your website!
- If you ever visit a page in your website and see a message saying "Port 3000 Not Found", that means your web server shut down for some reason. Toggle the Terminal pane back and start the server up again:

    ```bash
    ruby -run -ehttpd . -p3000
    ```

Happy hacking!
