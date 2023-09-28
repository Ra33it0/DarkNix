# CR4CKNIX
This is a Sha1 cracker for the Bip39 wordlist.

Usage

```shell
cd /cr4cknix
```
Build the package with Nix

```shell
nix build
```

To run the resulting package, which is an executable that prints to the terminal:

```shell
./result/bin/cr4cknix english.txt  <your_sha1hash> 
```

You should see this terminal output:

```text
Password found: yourword

```
