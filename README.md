# Torrent Client in Python

This project is a simple BitTorrent client implemented in Python. It includes functionalities for decoding and encoding bencoded data, interacting with a tracker, and downloading torrent pieces.

## Features

- **Bencode Encoding/Decoding**: Encode and decode bencoded data, which is the format used in `.torrent` files.
- **Tracker Communication**: Interact with a tracker to get a list of peers.
- **Piece Downloading**: Download pieces of the torrent from peers.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/YourUsername/torrent_client.git
    cd torrent_client
    cd app
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```
