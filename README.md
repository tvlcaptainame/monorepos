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

That member is now ready to code
; obviously following their normal workflow patterns 
(like creating a feature branch, etc.)