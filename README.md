# hash_cracking_ctf
***
<h1>Step-by-Step Exploitation Guide</h1>

***
Phase 1: run exploit.py
```bash
python3 exploit.py

# Enter Base64 payload: <ENTER YOUR HASH>
```
This payload can save final_hash.txt

Phase 2:
```bash
hashcat -m 10900 final_hash.txt /usr/share/wordlists/rockyou.txt

# Done! congratulations you crack the hash
```
