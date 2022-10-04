# Config-Escritorio
Configuración de Escritorio Junto Con Kitty Terminal

# Configuración De KittyTerminal

* Para la instalación de KittyTerminal vamos a realizar el siguiente comando: 

```
sudo apt-get install kitty

```
* Tenemos dentro de los repositorios la version de kitty que queremos aunque lo podemos también buscar por github ya que tiene su propio repositorio.

* Una vez tenemos instalado kitty vamos ahora a realizar la configuración de la terminal. Para ello simplemente tenemos que irnos a la ruta ~/.config/kitty y pegar los dos ficheros que tenemos en el repositorio, con esto sería suficiente.

# Mejoras para la terminal

* En caso de querer tener zsh con la powerlevel10k y eso, deberías de realizar los siguientes pasos:

* Primero de todo vamos a instalar la terminal zsh, luego de instalarla la ponemos por defecto sobre bash

* Luego una vez que la tenemos instalamos powerlevel10k vamos a instalar unos plugins sobre ~/.zshrc (fichero que tenemos también que descargar con mi configuración desde el repositorio)

* Finalmente ya tendríamos nuestra terminal lista y configurada ( los plugins de zsh se pueden encontrar en github todos con su método de instalación definido). Simplemente como paso final podemos poner la kitty como aplicación preferida de terminal y listo.

# Comandos para instalación de los plugins
* Instalación de hack-nerd-fonts ( Dentro de sudo su)
```
cd /usr/share/fonts
mv /home/user/Descargas/3270.zip .
unzip 3270.zip
rm 3270.zip
```
* Instalación de powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```
`
* Para la instalación de zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```
* Para la instalación de zsh-syntax
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh/zsh-syntax-highlighting

```
* Para la instalación de zsh-sudo
```
git clone https://github.com/hcgraf/zsh-sudo.git ~/.zsh/zsh-sudo

```
* Para la instalación de zsh-colored-man
```
git clone https://github.com/ael-code/zsh-colored-man-pages.git ~/.zsh/zsh-colored-man-pages
```
