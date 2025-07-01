# Install VIM

## MacOS
```
$ brew install vim
```

## Debian/Ubuntu
```
$ sudo apt update -y && sudo apt install vim -y
```

# Setup vimrc
```
$ git clone git@github.com:bakharevd/vimrc-devops.git
```
```
$ cd vimrc-devops
```
```
$ bash install.sh
```

# Shortcuts

The **Leader key** is a way of extending the power of VIM's shortcuts by using sequences of keys to perform a command. The default leader key is **comma** (`,`) key.

| Key | Description |
| --- | --- |
| `Ctrl-i` | Toggle IDE mode in VIM |
| `Ctrl-g` | Enable Git Gutter |
| `Ctrl-f` | Toggle Fullscreen mode |
| `Ctrl-t` | Toggle NerdTree |
| `Ctrl-n` | Move focus to NERDTree window |
| `Ctrl-d` | Toggle Terminal below current tab |
| `,cc` | Comment out the current line or text selected in visual mode. |
| `,cu` | Uncomments the selected line(s). [Read More](https://github.com/preservim/nerdcommenter#default-mappings) |

# Supported Languages

- Dockerfile
- Golang
- HCL
- Markdown
- Nginx
- Python3
- Terraform
- TOML
- Vagrant
- YAML
