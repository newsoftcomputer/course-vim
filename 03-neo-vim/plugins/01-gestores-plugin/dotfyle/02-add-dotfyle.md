
# Add DotFyle

Para instalar Dotfyle en Neovim, sigue estos pasos:

## 1 Instalar Neovim: Asegúrate de tener Neovim instalado. Puedes instalarlo usando tu gestor de paquetes preferido. Por ejemplo, en Ubuntu:

    sudo apt install neovim

## 2 Instalar un gestor de plugins: Dotfyle requiere un gestor de plugins como vim-plug. Instálalo con el siguiente comando:

    $ curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

## 3 Configurar Dotfyle: Añade Dotfyle a tu configuración de Neovim. Abre tu archivo de configuración de Neovim (init.vim o init.lua) y añade la configuración para Dotfyle. Aquí tienes un ejemplo usando vim-plug:
    
    call plug#begin('~/.vim/plugged')
    Plug 'codicocodes/dotfyle'
    call plug#end()


### 4 Instalar los plugins: Abre Neovim y ejecuta el comando :PlugInstall para instalar Dotfyle y cualquier otro plugin que hayas añadido.

    - Configurar Dotfyle: Sigue las instrucciones específicas de Dotfyle para configurarlo según tus necesidades. Puedes encontrar más detalles en la página de GitHub de Dotfyle1.

    - Si necesitas más ayuda con la configuración o tienes alguna otra pregunta, ¡házmelo saber!