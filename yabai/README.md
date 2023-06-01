# Initialize Yabai and skhd
## Install Yabai
Run the following command:
```shell
brew install koekeishiya/formulae/yabai
```

## Install skhd
Run the following command:
```shell
brew install koekeishiya/formulae/skhd
```

# Configure the Yabai
## Create a yabai config file
Create directory and yabai config file
```shell
mkdir ~/.config/yabai
touch ~/.config/yabai/yabairc
```

## Add configuration options to file
Copy `yabairc` file to config directory
```shell
cp ./yabairc ~/.config/yabai
```

## Run services action for yabai
Start Yabai
```shell
yabai --start-service
```
Restart Yabai
```shell
yabai --restart-service
```
Stop Yabai
```shell
yabai --stop-service
```

# Configure the skhd
## Create a skhd config file
Create directory and skhd config file
```shell
mkdir ~/.config/skhd
touch ~/.config/skhd/skhdrc
```

## Add configuration options to file
Copy `skhdrc` file to config directory
```shell
cp ./skhdrc /.config/skhdrc
```

## Run services action for skhd
Start skhd
```shell
skhd --start-service
```
Restart skhd
```shell
skhd --restart-service
```
