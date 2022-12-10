<div align="center">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fuas.edu.kw%2Fwp-content%2Fuploads%2F2018%2F12%2Ffolder-icon.png&f=1&nofb=1&ipt=d46988ac4df1272c9477880b5a5d6695f364a7939d1409f240f52829504906cf&ipo=images" width="140px" heidht="140px">
  <h2>My dotfiles</h2>
  <p>My settings for programs I use in my development environment.</p>
</div>

```sh
    ### Download Ubuntu
      wsl --list --online && wsl --install -d Ubuntu-20.04
      
    ### Oh My Zsh
      <username>    ALL=(ALL:ALL) NOPASSWD:ALL
      sudo apt update -y && sudo apt upgrade -y
      sudo apt install zsh -y
      sudo apt install git
      sudo apt-get install powerline fonts-powerline -y
      chsh -s /bin/zsh
      sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

    ### Zi
      sh -c "$(curl -fsSL git.io/get-zi)" -- -i skip -b main
      
    ### NVM
      curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      source ~/.bashrc

    ### Spaceship
      git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
      ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"

    ### Hyper
      git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions
      git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
      git clone https://github.com/krve/hyper-mac-controls.git
      git clone https://github.com/getomni/hyper.git
      sudo apt install fasd -y

```