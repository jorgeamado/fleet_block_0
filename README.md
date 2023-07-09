# Your Project Name

In order to initialize and set up this project for development, follow the steps outlined below:

## Set Up

1. **Install Git LFS**

    Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.

    To install Git LFS, you can use the command below:

   ```bash    
   git lfs install
   
   ```
2. **Download Git Submodules**

   If your project uses Git submodules, you'll have to initialize and update them.

   You can use this command to download and initialize your submodules:

    ```bash
    git submodule update --init --recursive
    ```

3. **Run install-hooks**
    
   This is necessary to set up hooks that will catch uncommitted meta files and empty directories.
   You can use the following command to accomplish this:

      ```bash
      ./install-hooks.sh
      ```
Ensure you run these steps in the exact order to avoid any conflicts.

After following these steps, your project should be ready for development.
