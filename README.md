# Command for starting watchface project
new-project watchface

# Command for entering wsl directory
sudo mount -t drvfs C: /mnt/c

cd /mnt/c

# Command for building and running the faces
pebble build

pebble install --emulator basalt (replace basalt with name of watch you want to test)
