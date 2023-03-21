# Running Jekyll Locally

To start running Jekyll on your local machine, follow these steps:

1. Install Jekyll by following the [official installation guide](https://jekyllrb.com/docs/installation/).
2. Clone your website repository to your local machine using Git. For example, if your repository is called `my-website`, you can clone it by running:

    ```
    git clone https://github.com/your-username/my-website.git
    ```

3. Navigate to the root directory of your website by running:

    ```
    cd my-website
    ```

4. Switch to the `_primary_edits` branch if you want to make edits to your website. This branch is where you can make changes without affecting the main website. For example, run:

    ```
    git checkout _primary_edits
    ```

5. Start Jekyll with live reload and trace features by running:

    ```
    bundle exec jekyll serve --trace --livereload
    ```

6. Open your web browser and go to `http://localhost:4000` to view your website.

Remember to switch back to the `_primary` branch and merge any changes from `_primary_edits` once you're satisfied with your edits. For example, run:

```
git branch 
git switch _primary_edits # And then do your editing
git switch _primary
git merge _primary_edits
```

I hope this helps jog your memory on how to get started with editing your website again!

