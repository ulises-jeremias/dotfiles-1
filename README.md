# Mikroways dotfiles

Este archivo mantiene las configuraciones sugeridas de algunas de las
aplicaciones que usamos en Mikroways.
La forma de instalar estos dotfiles es tan simple como ejecutar:

```bash
git clone https://github.com/Mikroways/dotfiles.git ~/.dotfiles-mw
~/.dotfiles/scripts/install
```

Luego de correr los comandos anteriores se configurarán algunos programas
utilizados desde la consola como por ejemplo:

* zsh
* vim
* git
* tmux

## Pasos manuales requeridos

El archivo gitconfig.local es necesario que se edite manualmente con los datos
personales. Por ejemplo

```ini
[user]
  name = Juan Perez
  email = juan.perez@mikroways.net
```

> Se provee un archivo `gitconfig.local.sample` a modo de ejemplo que puede
> copiarse como `gitconfig.local` y volver a correr el archivo

## Cómo usar este repositorio

La idea es que cada integrante de Mikroways utilice este repositorio como punto
de partida, pero personalice su ambiente como mejor le parezca, agregando nuevas
configuraciones y proponiéndolas al repositorio raiz, compartiendo experiencias
que nos hagan más eficientes en el día a día.
Para ello se puede forkear este repositorio y cualquier contribución realizarla
como un Pull Request.
