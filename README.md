# badger
Badger, badger, badger, badger, badger, badger, badger, badger, badger, badger, mushroom, mushroom!

sudo apt update
sudo apt install -y \
    build-essential \
    clang \
    llvm \
    libx11-dev \
    libxcursor-dev \
    libxinerama-dev \
    libxrandr-dev \
    libxi-dev \
    libgl1-mesa-dev \
    libasound2-dev \
    libpulse-dev

    ./odin run examples/demo/square_badger_v7.odin -file

# -opt:3 enables high-level optimizations
# -out:game names the resulting file
odin build examples/demo/square_badger_v7.odin -opt:3 -out:game
