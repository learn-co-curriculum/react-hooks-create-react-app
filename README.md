# Create React App

## Problem Statement

So far, through this React course, a basic framework of files has been provided
in the labs. In order for React to work, a specific file structure is required.
Having to set all that up every time can be a bit of a pain and is also prone to
error. On top of this, copying and pasting old React projects means you may miss
out on the most up-to-date React features.

Fortunately, the creators of React have also set up a handy tool for rapidly
creating the barebones file structure we need for React apps. In this lesson, we
will be discussing how to use the `create-react-app` node package to get our own
projects off the ground.

## Objectives

- Ensure `npm` is updated to utilize newly included `npx` command
- Review how to create a react app using `create-react-app`

#### Keeping Up To Date

Before we continue, it is recommended you run `npm install -g npm`. This will
make sure you have the newest version of Node Package Manager. Once this is
installed, you should now have access to `npx`. Instead of having to globally
install a node package using `npm`, with `npx`, we can provide a node package
name as an argument and use remote node packages as though they were installed.

Since you're grabbing the package remotely, you will be getting the most up to
date version of it by default!

#### Creating A React App From Scratch

In your terminal, navigate to a location where you would like your React app
directory to be located.

Decide on a name for your app. Once you've got one, run the following with your
app's name in place of `<your_app_name>`:

```js
npx create-react-app <your_app_name>
```

The `create-react-app` package sets up the basic file structure and
executes an initial `npm install`.

#### Conclusion

That's it! Fast and easy. The app is ready to run with `npm start`, and will
display some default content. The `README.md` file provided also has a very
detailed breakdown of all the additional features that come with
`create-react-app`.

One feature that is included: a service worker that allows the app to cache page
data in a user's browser. The result? After a user visits your site once, if they
do not have service, they _can still go to your website and see content_. The
cache will display what the site looked like the last time the user was there!

While it is perfectly fine to set up your own React files, `create-react-app` is
a handy solution to quickly get past any setup and get straight to designing
your app. Since it is actively maintained by Facebook, you're also always
getting a nicely polished, up-to-date base for your React applications!
