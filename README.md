# react-native-dynamic-link-example

A simple to project to explain use of dynamic link through firebase.

Open browser on emmulator and type https://ttrc.page.link/sample. It will redirect you to Courses page. 

But if you open app, It will open home page.

Open browser on emmulator and type https://ttrc.page.link/12345. It will redirect you to Courses page. But this time the content will be written as `Courses of Sample3 App : 20`. Last time on link https://ttrc.page.link/sample, the content was `Courses of Sample3 App : 20`. It means this 15 and 20 can be anything (any id or unique key) that you will specify on firebase dynamic link. Based on this you can control the contents of your page.

## Important Links to study 

[RN Firebase](https://rnfirebase.io/dynamic-links/usage)

