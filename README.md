# Personal bin scripts

## Configurations

1. create a dir inside home directory `mkdir bin`;
2. add path to local environment. Add this line `export PATH=$PATH":$HOME/bin"` in .bash_profile;
3. bind the modify with command `source /path/.bash_profile`;
4. create an executabale file (`chmod +x namefile`) inside bin dir;
5. implement whatever script do you want inside it;
5. all is done;
6. now you can use your name file as a command in your terminal.

## Options
In my case I've been created a `pt` script with manage different options:

- `pt new-repo name-repository`: create a new repository in local. Create `.gitignore` and `README.md` inside it. Add these files and do the first commit. If you provide an url for the repository in remote like `https://github.com/user/repo.git`, script bind it and push all to the server.

## TODO

- [x] write configurations section;
- [x] write options section;
- [ ] write examples section;
