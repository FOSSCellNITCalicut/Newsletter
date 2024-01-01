# FOSSCellNITC Newsletter
The html template for Newsletter and Blog built with hugo.

## How to Contribute
1. Clone the repository

```bash
git clone https://github.com/FOSSCellNITC/Newsletter.git
```


2. Install hugo
    For Arch based distros
    ```bash
    sudo pacman -S hugo
    ```
    For Debian based distros
    ```bash 
    sudo apt install hugo
    ```
    For Fedora
    ```bash
    sudo dnf install hugo
    ```
    For other platforms, check [here](https://gohugo.io/getting-started/installing/)
3. Start the hugo server after navigating to the repository
    ```bash
    hugo server
    ```
    The server will be running at `localhost:1313`


4. Create a new post
    ```bash
    hugo new post/<post-name>.md
    ```
    The post will be created in the `content/posts` folder

5. Edit the post in the `content/post` folder

6. Add images to the `static` folder. Refer to the existing posts for the image path
    
7. Run `hugo` to build the site
    ```bash
    hugo
    ```
    The site will be built in the `public` folder

8, Run `hugo serve` to serve the site

    The site will be served at `localhost:1313`

9. Push the changes to the repository
    ```bash
    git add .
    git commit -m "commit message"
    git push origin main
    ```

