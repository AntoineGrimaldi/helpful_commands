- update time &rarr; `sudo date -s "$(wget -qSO- --max-redirect=0 google.com 2>&1 | grep Date: | cut -d' ' -f5-8)Z"`
- empty trash &rarr; `rm -rf ~/.local/share/Trash/*`
