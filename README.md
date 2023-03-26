# EasySpecter

A simple specter for Minecraft Bedrock Edition based on [gophertunnel](https://github.com/Sandertv/gophertunnel)

# How to use

- Step 1
    + Install [EasySpecter](https://github.com/nhanaz/EasySpecter/releases)
- Step 2
    + Run `EasySpecter.exe`

# Commands
- `xbox login` login xbox account
- `xbox join <ip:port>` Spawn specter to server with xbox account
- `join <name> <ip:port>` Spawn specter with `<name>` and non xbox account (must disable `xbox-auth` in server)
- Specter commands:
    + `specter chat <specter name> <message>` : Specter will chat `message`
    + `specter move <specter name> <x> <y> <z>` : Specter will move to `x, y, z`
    + `specter quit` : Disconnect specter
    + `specter list` : List specters

# Using as library

- Get a package

    ```
    go get github.com/nhanaz/easyspecter
    ```

- Create a specter
    + [Wiki](https://github.com/nhanaz/EasySpecter/wiki)
