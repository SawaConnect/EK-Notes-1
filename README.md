### EK-Notes-1


` sudo dpkg-reconfigure tzdata `

` sudo adduser sc-user `

` sudo usermod -aG sudo sc-user `

---
#### Install fail2ban

` sudo apt update `

` sudo apt install fail2ban `

` sudo systemctl status fail2ban `

`  sudo fail2ban-client status sshd`

#### Fail2ban Configuration --- config directory /etc/fail2ban --- first copy jail.conf to jail.local

` sudo cp /etc/fail2ban/jail.{conf,local} `


#### Check listening ports

` netstat -tupln `

#### Note

` sudo `

#### Note

` sudo `

---

#### How to show all banned IP with fail2ban?

` awk '($(NF-1) = /Ban/){print $NF}' /var/log/fail2ban.log | sort | uniq -c | sort -n `

---

` sudo fail2ban-client status sshd `

` sudo `

` sudo `

` sudo  `

` sudo `

` sudo  `

` sudo  `

#### Note

` sudo   `

` sudo  `

` sudo  `

` sudo  `
