# platformsh-example-drupal8-2-1
Example Platform.sh project with Drupal 8.2.1

Steps to use:

1. Clone this repo

    ```
    git clone https://github.com/r0fls/platformsh-example-drupal8-2-1.git
    cd platformsh-example-drupal8-2-1
    ```

2. Create a [platform](https://accounts.platform.sh/platform/buy-now). Choose to import your own code when it asks you and stop there.
3. Use the code in the bottom right from step 2 to push magento to your platform, which will look like this:

    ```
    git remote add remote <platform-git-url>
    git push -u platform master
    ```

4. Finally, go to /core/install.php path of your site's URL. If you click "Access site" above your build log, you will get to the site's URL. From there append the /core/install.php path to begin the drupal installation.
