# Port-knocker


  Exploit the vulnerability on a closed port configured with port knocking techniques to unlock a closed port using the port knocking bruteforce attack

  And can also act as a simple port knocking client

  It doesnt work on a server that uses single packet authorization or other types of cryptographic hashes as sequence packet 

  This tool can unlock a closed port with attempted connection using each sequence packet by using the itertool library for combination of each sequence

  Once you knock each port with sequence. You can run your Nmap to check wether the closed port you want to unlock is open

  If the port is not open then you can keep knocking the port with each sequence and keep using Nmap to monitor the port state........



# Command


 git clone https://github.com/Gbolahanomotosho/Port-knocker



 cd Port-knocker



 pip install -r requirements.txt




 python Port-knocker.py





# tested on :


- Kali linux


# Disclaimer: 

 

  I wont be responsible for any misuse use of this tool

  

  For educational purpose only...........
