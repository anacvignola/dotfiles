# :computer: :gear: dotfiles

Como eu adoro formatar o pc e mudo várias vezes de sistema operacional, decidi automatizar alguns processos ao menos para o windows. No momento estou utilizando o Windows 10 com [WSL](https://docs.microsoft.com/pt-br/windows/wsl/install) e nele sempre utilizo o gerenciador de pacotes [Chocolatey](https://chocolatey.org/).

## Como utilizar :

```bash
    ### No Windows

    instalar o gerenciador de pacotes [Chocolatey](https://chocolatey.org/)

    ### clone o repositório

        $ git clone https://github.com/anacvignola/dotfiles/

    ### instale os pacotes

        $ cd dotfiles

        $ choco install packages.config -y

    configure o [WSL](https://docs.microsoft.com/pt-br/windows/wsl/install) e instale o ubuntu

    ### instale as extensões do vscode com o comando abaixo

        $ code --install-extension clinyong.vscode-css-modules
        $ code --install-extension CoenraadS.bracket-pair-colorizer
        $ code --install-extension Dart-Code.dart-code
        $ code --install-extension Dart-Code.flutter
        $ code --install-extension dbaeumer.vscode-eslint
        $ code --install-extension donjayamanne.githistory
        $ code --install-extension EditorConfig.EditorConfig
        $ code --install-extension esbenp.prettier-vscode
        $ code --install-extension formulahendry.auto-close-tag
        $ code --install-extension formulahendry.auto-rename-tag
        $ code --install-extension formulahendry.code-runner
        $ code --install-extension ms-vscode-remote.remote-wsl
        $ code --install-extension ms-vsliveshare.vsliveshare
        $ code --install-extension naumovs.color-highlight
        $ code --install-extension octref.vetur
        $ code --install-extension PKief.material-icon-theme
        $ code --install-extension ritwickdey.LiveServer
        $ code --install-extension rocketseat.rocketseatreactjs
        $ code --install-extension rocketseat.rocketseatreactnative
        $ code --install-extension rocketseat.theme-omni
        $ code --install-extension styled-components.vscode-styled-components
        $ code --install-extension WakaTime.vscode-wakatime

    ### substituir settings.json do vscode, .hyper do Hyper Terminal

    ### acessar PowerShell em modo admnistrador e:

        $ code $PROFILE

    ### e cole:

        Import-Module oh-my-posh
        Set-PoshPrompt -Theme agnoster
        Enable-PoshTooltips

    ### e só salvar.

    ### No Ubuntu

        $ sudo apt-get install git zsh

    também instale [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) e [NVM](https://github.com/nvm-sh/nvm)

    ### instale o node no ubuntu

        $ nvm install --lts

    ### clone novamente o dotfiles no ubuntu e crie links simbólicos

        $ git clone https://github.com/anacvignola/dotfiles/

        $ ln -s ~/.dotfiles/.bashrc ~/.bashrc
        $ ln -s ~/.dotfiles/.zshrc ~/.zshrc
        $ ln -s ~/.dotfiles/.gitconfig ~/.gitconfig

    ### após a instalação

      $ flutter doctor --android-licenses

```

Eu utilizo o tema [Omni](https://github.com/getomni) em praticamente tudo, e a fonte que utilizo [JetBrains Mono](https://www.jetbrains.com/lp/mono).

### Alguns links:

- [Awesome Hyper](https://github.com/bnb/awesome-hyper)
- [Oh my posh](https://ohmyposh.dev/)
- [Tutorial configuração emulador](https://react-native.rocketseat.dev/)
- [Tutorial Terminal Oh my zsh](https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/)
