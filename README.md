# Instalação e uso do GNOME Network Displays via FlatPak

## Passo 1: Instalar o Gerenciador de Pacotes Flatpak

Primeiro, instale o gerenciador de pacotes **Flatpak** com o comando no terminal:

```bash
   sudo apt install flatpak 
 ```


## Passo 2: Instalar o  **GNOME** Networks Displays

Logo após, instale o GNOME Network Displays usando o Flatpak com o seguinte comando no terminal:
 
 ```bash
    flatpak install --user https://flathub.org/repo/appstream/org.gnome.NetworkDisplays.flatpakref
 ```

## Passo 3: Atualizar o **GNOME** Networks Displays

Para atualizar, ultilize o comando:
```bash
  flatpak --user update org.gnome.NetworkDisplays
```
## Passo 4: Rodar o Programa

Para rodar o programa, ultilize o comando no terminal:
```bash
flatpak run org.gnome.NetworkDisplays
```
