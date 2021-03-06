# Angular2-Samples

<div lang="fa" dir="rtl" align="right">
این مخزن جهت سورس کد پروژه های دوره آموزش آنگولار در آکادمی وب نگار ایجاد شده است
جهت اطلاعات بیشتر می توانید به آدرس ["دوره آموزشی فارسی آنگولار آکادمی وب نگار"](http://academy.webnegar.ir/Angular) مراجعه نمایید
</div>
Materials for the ["Angular 2: Getting Started"](http://academy.webnegar.ir/Angular) course on Webnegar.

`01 - Start`: The starter files set up for use in VSCode, WebStorm, or other editors. Use this to code along with the course. (Updated for <i>Angular 2 final</i>)
فایل ها را می توانید در ویژوال استادیو کد یا دیگر ادیتورهای مورد علاقه استفاده کنید

`02 - Final`: The completed files. Use this to see the completed solution from the course. (Updated for <i>Angular 2 final</i>)


See the `README.md` file under each folder for details on installing and running the application.
<div lang="fa" dir="rtl" align="right">
فایل فوق در هر پوشه حاوی دستورالعمل و جزئیات نصب و راه اندازی  برنامه است
</div>

If you have any problems installing or running this code, please see the ["Angular 2: Getting Started Problem Solver"](http://academy.webnegar.ir/Angular)
<div lang="fa" dir="rtl" align="right">
هر نوع اشکال در نصب و راه اندازی این کد ها را با ما در میان بگذارید
</div>

If that does not resolve your issue, please post to the [discussion board for the course](http://academy.webnegar.ir/Angular)

NOTE: The installation was tested using node v6.5.0 and npm 3.10.6.


This repository holds the TypeScript source code of the [angular.io quickstart](https://angular.io/docs/ts/latest/quickstart.html),
the foundation for most of the documentation samples and potentially a good starting point for your application.

It's been extended with testing support so you can start writing tests immediately.

**This is not the perfect arrangement for your application. It is not designed for production.
It exists primarily to get you started quickly with learning and prototyping in Angular**

We are unlikely to accept suggestions about how to grow this QuickStart into something it is not.
Please keep that in mind before posting issues and PRs.

## Prerequisites (پیش نیازات)

Node.js and npm are essential to Angular development. 
    
<a href="https://docs.npmjs.com/getting-started/installing-node" target="_blank" title="Installing Node.js and updating npm">
Get it now</a> if it's not already installed on your machine.
 
**Verify that you are running at least node `v4.x.x` and npm `3.x.x`**
by running `node -v` and `npm -v` in a terminal/console window.
Older versions produce errors.

We recommend [nvm](https://github.com/creationix/nvm) for managing multiple versions of node and npm.

## Create a new project based on the QuickStart (ایجاد پروژه جدید)

Clone this repo into new project folder (e.g., `my-proj`).
```shell
git clone https://github.com/webnegar/Angular2  my-proj
cd my-proj
```
## Install npm packages (نصب پکیج ها)

> See npm and nvm version notes above

Install the npm packages described in the `package.json` and verify that it works:

```shell
npm install
npm start
```

>Doesn't work in _Bash for Windows_ which does not support servers as of January, 2017.

The `npm start` command first compiles the application, 
then simultaneously re-compiles and runs the `lite-server`.
Both the compiler and the server watch for file changes.

Shut it down manually with `Ctrl-C`.

You're ready to write your application.
