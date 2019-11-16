1. Clonse this repo.
2. Recursively update all Git submodules in the repository to install Docsy and related dependencies:
   ```
   git submodule update --init --recursive
   ```
3. Install npm packages:
   ```
   sudo npm install -D --save autoprefixer
   sudo npm install -D --save postcss-cli
   ```
4. `hugo server -D` (You will need hugo extended from https://github.com/gohugoio/hugo/releases)
