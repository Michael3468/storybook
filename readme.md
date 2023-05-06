# **Storybook**

## **UI-Kit components library**

Copy **`.storybook`** folder to root folder of your project

To create a submodule folder in your project if it does not already exist, go to your project root folder and type the following command:

```
git submodule add https://github.com/WhiteDevilMan/storybook src/stories
```

and then commit the changes

To retrieve submodule files, navigate to your project root folder and enter the following command:

```
git submodule update --init --recursive
```

and then in `src/stories`

```
npm install
```
