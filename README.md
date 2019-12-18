# This is some encrypted info generated as below command

1. encryption
``` shell
cat secret.txt | openssl enc -e -aes256 -out encrypted_data
```

2. decryption
``` shell
cat encrypted_data | openssl enc -d -aes256 -out secret.txt
```

Demo file is encrypted using my old common password.
