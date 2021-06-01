# Lesson 1: Overview and Warm-up on Useful Linux Commands

## Lesson URL
* https://missing.csail.mit.edu/2020/course-shell/

## Useful Linux Commands
* Show current date and time:
    ```
    $ date
    ```
* Show the arguments:
    * Space is used to seperate arguments, example:
    ```
    $ echo hello
    ```
    * Can use quotes (`""`) to integrate words w/ multiple words separated by spaces, example:
    ```
    $ echo "hello world"
    ```
    * Can also use backslash (`\`) to decorate the spaces, example:
    ```
    $ echo hello\ world
    ```
* Change directory to the path you were previously in, which is a handy way to toggle between different directories:
    ```
    $ cd -
    ```
* Open up a shell as root (super user):
    ```
    $ sudo su
    ```
* The amazing pipe (`|`), which can take the output if left side as the input the right side:
    ```
    $ curl www.google.com | tail # show the last row of www.google.com
    ```
* Open a file using an appropriate method:
    ```
    $ xdg-open <file name OR folder name> # in Linux
    $ open <file name OR folder name> # in MacOS
    ```

