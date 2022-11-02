# _Free CPU Cache_

&emsp;A simple linux bash script that deletes the temporary memory cache and frees up your RAM

&emsp;Note: current version of this scipt is only tested for debian based linux distros

## Installation

-   Download the source code and open it

-   Copy the `freecache` file and paste it in `/usr/bin`
    ```sh
    sudo cp ./freecache /usr/bin/freecache
    ```

    OR

-   [Add the location of `freecache` script to your `PATH`](#adding-script-to-path)

-   run `freecache` on your terminal

## Adding script to PATH

-   **Debian based systems:**
&emsp;open `.bashrc` file (located in `/home/user/`) using any text editor
&emsp;append the following lines to the file
&emsp;
```bash
export $PATH="/PATH/TO/THE/FILE_DIRECTORY:$PATH"
```
&emsp;save the file
&emsp;open terminal and run `source ~/.bashrc`
