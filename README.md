# podstawy linuxa - cwiczenia

## zadanie 1
* `wpisane'

## zadanie 2
* `mkdir praca`
* `mkdir cwiczenia`
* `/praca$ touch hello.txt`
* `/praca$ cp hello.txt cwiczenia`
* `/praca$ rm hello.txt`
* `rmdir praca`
* `/cwiczenia$ echo "This should be in front" > hello.txt`
* `/cwiczenia$ echo "This should be at the end" >> hello.txt`

## zadanie 3
* `/cwiczenia$ cd`
* `/cwiczenia$ ls ..`
* `/cwiczenia$ ls .`
* `/cwiczenia$ ls he*`
* `ls -F`
* `ls -i`
* `ls -R`

## zadanie 4
* `/cwiczenia$ man grep`
* `/cwiczenia$ man grep | head -10`
* `/cwiczenia$ man grep | tail -5`

## zadanie 5
* `sudo cat $(find / -name boot.log 2>&1 | grep -v "Permission")`

## zadanie 6
* `find /home/`
* `find /home/ -size +1M`
* `find ~ | grep "hello" | sort`

## zadanie 7
* `find ~ -mtime 0 > all_today`
* `find /etc | grep "net" > find_etc`

## zadanie 8
* `passwd nowy_uzytkownik`
* `sudo login`
* `whoami`

## zadanie 9
* `sudo usermod -a -G nowa_grupa grzegorzg`
* `sudo usermod -a -G nowa_grupa nowy_uzytkownik`
* `cut -d: -f1 /etc/group | sort | grep "nowa_grupa"`
* `getent group nowa_grupa`

## zadanie 10
* `echo "jakis tekst" > nowy_plik`
* `cat nowy_plik`
* `sudo login nowy_uzytkownik`
* `sudo chmod u+rwx /home/grzegorzg/nowy_plik`
* `sudo login`
* `ls nowy_plik.txt`
* *ls: cannot access 'nowy_plik.txt': No such file or directory*
* `sudo chmod o+rwx /home/grzegorzg/nowy_plik`
* `nano nowy_plik`
* `sudo chmod g+rwx /home/grzegorzg/nowy_plik`
* `sudo chmod o-rwx /home/grzegorzg/nowy_plik`
* `nano nowy_plik`

## zadanie 11
* `sudo userdel -f nowy_uzytkownik`
* `cd /home/`
* `ls`
* `getent group nowa_grupa`
* `groupdel`
* `sudo groupdel nowa_grupa`
* `ut -d: -f1 /etc/group | sort | grep "nowa_grupa"`

## zadanie 12
* `sleep 1000`
* `ps -e | grep sleep`
* `kill 20269`
* *Terminated*







