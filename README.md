# MRI Volume Slice

A 3 axis viewer or 3d volumes right in the broswer. Currently supports loading in Nifti (.nii) files. When you click and drag on any of the 3 axis, the other two axis update to display a slice at the coordinates of the mouse.

[Currently Live Here!](https://mrislice.netlify.com)

![3 view MRI display](https://res.cloudinary.com/irevdev/image/upload/v1539009277/MRI-Volume-Slice/fMRIexample2.gif "3 view MRI display")

This kind of three axis viewer is common in neuro science, but in the spirit of accessibility, open-source and open-science; here is an open-source viewer on the universal platform (the web browser).

At the moment this is very much a hobby project of mine, so you can expect bugs. Feel free to contact me.

## contributions and development

If you're not a developer but have ideas for how this can be used, or ways to extend it's functionality feel free to let me know 😁 🙌

### Setup for seasoned devs

``` 
git clone . . . 
npm install
parcel index.html
```

### detailed setup

You will need to install [git](https://git-scm.com/) and [node](https://nodejs.org/en/), go to the each of their websites to get them running on your OS.

Clone this repo

`git clone https://github.com/Irev-Dev/MRI-Volume-Slice.git`

Install parcel globally

`npm install -g parcel-bundler`

Install dependencies

`npm install`

Use parcel to build the project

`parcel index.html`

Parcel will also setup a live sever, so you can view the project by going to local host port 1234 (by default) ie [http://127.0.0.1:1234/](http://127.0.0.1:1234/). It will also live update any changes you make to the files.

