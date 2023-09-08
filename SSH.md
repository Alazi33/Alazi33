###**How to SSH into VM**

>_This is a quick guide on how to ssh from Windows 11 to a Kali VM. Just follow the steps bellow_

1. First, start windows and log into your Kali vm.
2. In the Kali vm, open a terminal and run apt update && apt upgrade.
3. Following that, do your check-change-check for ssh and start the service:
	* netstat -natp
	* sudo systemctl status ssh.service
	* sudo systemctl start ssh.service
	* sudo systemctl status ssh.service
	* netstat -natp
4. If everything checks out, then move to windows, start a command prompt, and run the following command.
	*ssh alazar@192.168.228.128
5. You will be asked for a password and once you provide it, the connection will be established.

>**Congrats, you just used ssh**
