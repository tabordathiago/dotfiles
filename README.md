# dotfiles

## Requirements:

- Install Zsh

```bash
sudo apt install zsh -y
```

- Install Oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- Install Starship
```bash
sh -c "$(curl -fsSL https://starship.rs/install.sh)"
```

- Install Font "JetBrainsMono Nerd Font"
```bash
https://www.nerdfonts.com/font-downloads
```

## Configuration:

- Crie o seguinte arquivo e cole o conteúdo do [starship.toml](starship.toml) nele:
```bash
mkdir -p ~/.config && touch ~/.config/starship.toml
```

- Adicione o conteúdo do arquivo [.zshrc](.zshrc) e a linha a seguir no final do ***seu*** arquivo ~/.zshrc:
```bash
eval "$(starship init zsh)"
```

<br />

<p align="center">
  <img src="https://user-images.githubusercontent.com/67063982/152066751-2d391467-40e1-4501-a3cd-e26d8e7002d1.PNG" />
</p>

