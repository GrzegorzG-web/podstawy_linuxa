# podstawy linuxa - cwiczenia

## zadanie 1

## zadanie 2

## zadanie 3

## zadanie 4

## zadanie 5

## zadanie 6

## zadanie 7

## zadanie 8

## zadanie 9

## zadanie 10
`echo "jakis tekst" > nowy_plik`
`cat nowy_plik`
`sudo login nowy_uzytkownik`
`sudo chmod u+rwx /home/grzegorzg/nowy_plik`
`sudo login`
`ls nowy_plik.txt`
*ls: cannot access 'nowy_plik.txt': No such file or directory*
`sudo chmod o+rwx /home/grzegorzg/nowy_plik`
`nano nowy_plik`
`sudo chmod g+rwx /home/grzegorzg/nowy_plik`
`sudo chmod o-rwx /home/grzegorzg/nowy_plik`
`nano nowy_plik`

## zadanie 11
`sudo userdel -f nowy_uzytkownik`
`cd /home/`
`ls`
`getent group nowa_grupa`
`groupdel`
`sudo groupdel nowa_grupa`
`ut -d: -f1 /etc/group | sort | grep "nowa_grupa"`

## zadanie 12
`sleep 1000`
`ps -e | grep sleep`
`kill 20269`
*Terminated*







