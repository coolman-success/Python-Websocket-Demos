
# Python Websocket Demos

## Table of Contents

- [Install Dependencies](#install-dependencies)
- [Ex1](#ex1)
- [Ex2](#ex2)
- [References](#references)

## Install Dependencies

```python
pip install -r requirements.txt
```

## Ex1

### Simple websocket client and server scripts

`client.py` sends message `Hello Server!` to the websocket server run by `server.py` once a connection to the server is established. And the server returns the message ("Hello Server!") back to the client.

### Run

- Run websocket server
    ```python
    python ex1/server.py
    ```
- Run websocket client
    ```python
    python ex1/client.py
    ```

## Ex2

### Connect Four Board Game

### Run

- Run websocket server
    ```python
    python ex2/app.py
    ```
- Run websocket client (http server)
    ```python
    python -m http.server --directory ex2
    ```

### References

- `ex1` is created following [ParametricCamp's websocket tutorial](https://youtu.be/tgtb9iucOts?list=PLx3k0RGeXZ_wZ_gYpYXfH6FTK7e0cDL0k)
- `ex2` was referenced from Python [websockets package documentation](https://websockets.readthedocs.io/en/stable/index.html)
