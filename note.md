No clipboard cli app by default, so install

```sh
sudo apt install xclip 
```

To use outside of terminal

```sh
cat text.txt | xclip -selection clipboard
# then ctrl + v
# and ctrl + c from outside terminal then
xclip -selection clipboard -o
```

