<h1>Hekto</h1>

Algorithm of development:

1. By default we're on master branch. For each section we create separate branch and move to it with command <b>"git checkout -b your_branch_name"</b> (your_branch_name - name of your branch).

2. Then after development of your section (or some other part of your site), we want to check it for validity (make it with the commands below at the same order: html, then css).

3. After that we want to to prepare the content staged for the commit. For that use <b>"git add ."</b>. That means that we want to stage all changes that we make.

4. Then, we need to write commit message - message that describe changes. For that use <b>"git commit -m 'YOUR MESSAGE'"</b>, where "YOUR MESSAGE" - it's your message. For commits we will use <a href="https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13" target="_blank">Conventional Commit Messages</a><br>
   For example:

   - if we developed new section or added some new functionality that doesn't exist before that, our message will be: <b>'feat: make a hero section'</b>;
   - if we fixed some bug or error, our message will be: <b>'fix: fix bug with styles'</b>;

5. After make a commit message, we can push our code and branch (because right now this branch is locally only) to our repository. When you make it for the first time you need to use <b>'git push --set-upstream origin YOUR_BRANCH_NAME'</b>, after that we can simply use <b>'git push'</b>

<h2>Commands</h2>
npm run html-check - checking all HTML files for validity <br>
npm run css-check - checking for order of CSS styles <br>
npm run css-fix - for fixing all order CSS styles problems
