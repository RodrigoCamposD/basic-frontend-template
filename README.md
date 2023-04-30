# BASIC FRONTEND TEMPLATE

Really simple template with Parcel, Bootstrap and Animate.css.

## 1. DOWNLOAD

You can just download, unzip in your machine and run `npm install` or use `git clone`:

### 1.1 Git Clone

Make sure to rename the repo folder, after you clone it, so that you don't confuse yourself later. Try renaming when you clone:

```bash
git clone CLONE_URL your_project_name
```

After you have cloned and renamed your repo, cd into the folder.

```bash
cd your_project_name
```

Next check your git remote origin.

```bash
git remote -v
```

It is pointing to this repo but you want it to point to your own. You need to remove the current remote and place your own in.

```bash
git remote remove origin
```

Next go to your Github page and make a new repo with the same name you just created locally. **Don't click Initialize this repository with a README**. Create Repo, then you will see two options, choose the second "push an existing repository from the command line", update what you need in `package.json` and follow the instructions.

```bash
git remote add origin your_github_project.git
```

## 2. INSTALL

```bash
npm install
```

## 3. RUNNING

For development:

```bash
npm run dev
```

To Build the bundle:

```bash
npm run build
```

## 4. NOTES

### 4.1 Before Build

Edit `index.html` (html lang, meta description, title, favicon) and add what you want like social media tags.
Check the others files too `.htaccess` and `sitemap.xml` if you need 😉
In the `main.js` you can find a simple code to animate stuff and show a "to top" icon.

### 4.2 After Build

After build the project check the sitemap name created with parcel in `scr/dist` folder and paste into the file `robots.txt`.

## RESOURCES

[https://getbootstrap.com/](https://getbootstrap.com/) Bootstrap

[https://animate.style/](https://animate.style/) Animate.css
