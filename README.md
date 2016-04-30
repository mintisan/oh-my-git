# Oh My [Git](https://git-scm.com/)

> some git config for easing my operation

1. Clone this [Repo.](https://github.com/mintisan/oh-my-git.git) to a path you like, such as `HOME` or anywhere you want:

    ```
    git clone https://github.com/mintisan/oh-my-git.git ~/oh-my-git
    ```

2. Change the directory you just cloned(maybe `cd ~/oh-my-git`), and create symbolic link `.gitconfig` to `$HOME` path

    ```
    ln -s $PWD/oh-my-git/.gitconfig ~/.gitconfig
    ```
> When you execute `echo $PWD` in shell, you will know what the `$PWD` means.
> Yes, it means the path of current directory you stayed.
