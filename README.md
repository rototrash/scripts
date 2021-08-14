# scripts
_**Real simple**_ scripts to automate some of my simple tasks cuz I'm too lazy to do it everytime I break my linux install :)


## 1. `db-bt-pair.sh` : Copy Bluetooth Pairing Info File from Manjaro to Arcolinux and EndeavourOS.  

### Usage

Run the `db-bt-pair.sh` file as `su`, `sudo` won't work here.
```
$ su
Password:
# sh db-bt-pair.sh
```
## 2. `krohnkite-toggle.sh` : Toggle [Krohnkite](https://github.com/esjeon/krohnkite) (Dynamic Tiling extension for KWin) through terminal or a shortcut key.

### Usage

#### a. You can run the script from the terminal itself.
  1. Navigate to the folder containing the script
  2. Make the script executable first by `sudo chmod +x krohnkite-toggle.sh`.
  3. Execute the script by `sh krohnkite-toggle.sh`.
```
sudo chmod +x krohnkite-toggle.sh
sh krohnkite-toggle.sh
```
#### b. Execute the script via a shortcut-key.
  1. System Settings > Shortcuts > Custom Shortcuts > Create a new Command/URL Gloabal Shortcut
  2. Assign the Shortcut-Key under the `Trigger` Tab
  3. Add the execute command under the `Action` Tab. In my case: `sh /home/siddharth/.my-sh-scripts/krohnkite-toggle.sh`

