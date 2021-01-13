## Install

    sudo apt install tmux
    git clone https://github.com/thewind11235/cc-ddos.git
    cd cc-ddos
    pip3 install -r lib.txt

## Usage

    python3 cc.py
    
    tmux new-session -d -s "ddos1" && tmux send-keys -t "ddos1:0" "python3 cc.py" Enter
    
