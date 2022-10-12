# ELEC_SIGNATURE

This program is specifically used for creating signature with private keys and signing documents.

## USAGE

	cd src
    python ./main.py -a <action> [args]

To find out all the available arguments use
    
    python ./main.py -h

Available actions:
- sign: create signature for your file with your private key. Required args: -k (--key), -f (--file)
- verify: verify signature for your file with public key. Required args: -k (--key), -f (--file), -s (--signature)
- genkey: generate key pair for your signatures. Args: -p (--path) - path of directory for your key pair. default: ~/sign_keys
