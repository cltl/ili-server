# ili-server
Node.js server for querying the WordNet interlingual index (ILI)

## Setting up your own ILI server

1. run `setup.sh` to download the ILI index in this directory
2. install Virtuoso
3. update the paths in the files `server.js`, `commands.txt` and `reload.sh` to correspond to your local setup
4. run `reload.sh` to load your current ILI files
5. run `server.sh` to start the server on port 3333
