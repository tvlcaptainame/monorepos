## Bootstrap

Now say another member on the team wants to work on the project. 
They first globally install `lerna`.

```bash
sudo npm install --global lerna
```

They then clone the repository
and from the project’s root folder they run the following command 
to install all the dependencies (including the symbolic links).

```bash
lerna bootstrap --hoist
```


## Folders

```bash
npm create-react-app project
npm create-react-app styleguide
```

- components: A re-usable library of React components
- project: The web application
- styleguide: A style guide illustrating the use of components
