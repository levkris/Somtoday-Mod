# Contributing
Pull requests are welcome! Be clear about what you've changed, and I'll almost always approve it.

<br>

**Before you start, here's a few tips:**
- *If you want to contribute to Somtoday Mod, **you'll need to install the browser extension locally**. Either the Chromium or Firefox version.*
  - To do this, follow the steps described in README.md
- *Only modify one version of the code*
  - So if you're using Firefox, do not modify the Chromium version, and vice-versa
  - The other versions are automatically generated when I run the generation process
- *Do not touch the `// [GENERATION]` comments*
  - These are needed for the automatic code generation for the Android and userscript versions
- *Try to keep the file structure roughly the same*
  - It's not bad if you add files, but reorganizing the whole project is just a pain, since the generation process depends on the current structure

**Additionally, format your pull requests like this:**
- *Of course a fitting title*
  - Make sure the title states what you updated in your PR
- *Update your PR or send a comment with updated content whenever you change something to your PR*
  - This will make it easier to review whenever you have updated something
- *Use this as an example if you do not know where to start*
  - ```md
    ## Insert title that you used for the PR

    # If it fixed an issue based on any issue from the issues tab:
    - This PR fixes multiple issues:
      - What the issue is about, + based on issue #issueNumber (e.g. Night theme since the latest Somtoday Update, based on issue #41 )

    # If an update, and was not an issue:
    - This PR updated:
      - What you updated (e.g. Night theme svg, to make it look more modern)

    # If you added something new:
    - This PR introduced:
      - What you added (e.g. Added sounds whenever you get a notification)

    # If you add any edits to your PR after you have filed it, add this before you add more content:
    # EDITS:
    
    # After this, add any attachment if needed
    ```
  - You don't have to fill in everything, only whatever applies.
