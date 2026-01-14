## Week 01 - Day 02

### Concepts

### Notes
#### Preparing  install Ubuntu in Windows 11
- Win + R -> optionalfeatures
- Chek **Windows Subsystem for Linux**
- Check **Virtual Machine Platform**
- Restart machine


## Install Ubuntu (WSL)
- Open **PowerShell**
- Install WSL Ubuntu:
```bash
wsl --install
```
- Create user
- Create password
- Update:
```bash
sudo apt update && sudo apt upgrade -y
```

## Cloning a GitHub repository on Ubuntu
- Install Git:
```bash
sudo apt update
sudo apt install git
```
- Verify installation:
```bash
git --version
```
- Config User:
```bash 
git config --global user.name "HugoVsc"
git config --global user.email "hugodevasconcelos8@icloud.com"
```
- Change directory
```bash
cd ~/Documentos
```
- Clone public repository
```bash
git clone https://github.com/usuario/repositorio.git
```

### Commands
- pwd = Mostrar onde estou
- cd = acessar diretório
- ls = ver o que tem no diretório
- mkdir = criar diretório
- cat = exibir conteúdo completo de arquivos de texto puro (scripts, .txt, .md, .conf, etc.)
- lesss = exibir conteúdo aos poucos (logs)
- nano = editor de texto simples
- Salvar texto Nano = Ctrl + O
- Sair Nano = Crtl + X
