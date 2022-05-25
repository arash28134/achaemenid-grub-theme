![2022-05-25_15-04](https://user-images.githubusercontent.com/74412308/170269537-ccbb528d-7a27-4eeb-ad43-720ec82ab817.png)

# Supported Languages

This theme supports English, Farsi (Persian), French, German, Italian, Norwegian, Portuguese, Russian, Spanish, Turkish, Ukrainian, Chinese (simplified)

# Changing the language

- Change directory to where theme's .txt file is

  ```
  cd achaemenid-grub-theme/achaemenid
  ```

- Edit theme.txt
  ```
  nano theme.txt
  ```

- Find line 44 and comment out that line so it becomes like this:
  ```
  # text = "Booting in %d seconds"
  ```

- Find your preferred language and uncomment it (Farsi language in this case) so it becomes like this:
  ```
  text = "بوت کردن در %d ثانیه"
  ```

- Do the same for line 79. comment out the default text, and uncomment your preferred language

- Save the .txt file using CTRL+O and then Enter, and exit using CTRL+X and Enter

- Switch to parent directory and run the install script again
  ```
  cd ..
  sudo ./install.sh
  ```

# Installation
<b>First and main method of installation</b>

- Open terminal

- Clone this repository

  ```
  git clone https://github.com/arash28134/achaemenid-grub-theme.git
  ```

- Change directory to the Achaemenid Theme

  ```
  cd achaemenid-grub-theme
  ```

- Run installation script

  ```
  sudo ./install.sh
  ```

- Reboot your PC

<b>Second method of installation</b>

- Install Grub Customizer

  ```
  sudo add-apt-repository ppa:danielrichter2007/grub-customizer
  sudo apt-get update
  sudo apt-get install grub-customizer
  ```

- Go into the cloned repository
- Right click on acahemenid directory and choose "Compress" and then select .zip and hit Create

- Open Grub Customizer
- Go to Appearance settings tab
- Select Custom resolution and type in your resolution. E.g: 1920x1080
- Press Add theme button and then select the .zip file that you just made
- Save changes

- Reboot your PC
