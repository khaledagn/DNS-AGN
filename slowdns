#!/bin/bash
clear
slowdns () {
echo -e "\033[1;31m════════════════════════════════════════════════════\033[0m"
tput setaf 7 ; tput setab 4 ; tput bold ; printf '%40s%s%-12s\n' "SLOWDNS MANAGER MENU V3.0 (ENGLISH)" ; tput sgr0
echo -e "\033[1;31m════════════════════════════════════════════════════\033[0m"
echo -e "\033[0;36m#===================================================#\033[m"
echo -e "\033[0;36m# .|'''.|'||                '||''|. '|.   '|'.|'''.|#\033[m"
echo -e "\033[0;36m# ||..  ' ||  ... ... ... ...||   || |'|   | ||..  '#\033[m"
echo -e "\033[0;36m#  ''|||. ||.|  '|.||  ||  | ||    ||| '|. |  ''|||.#\033[m"
echo -e "\033[0;36m#.     '||||||   || ||| |||  ||    |||   |||.     '|#\033[m"
echo -e "\033[0;36m#|'....|'.||.'|..|'  |   |  .||...|'.|.   '||'....|'#\033[m"
echo -e "\033[0;36m#---------------------------------------------------#\033[m"
echo -e "\033[0;36m#\033[m \033[0;31mDEVELOPED BY @LAAEL | TRANSLATED AND MODDED BY @KHALEDAGN | TG CHANNEL @KHALEDAGN\033[m \033[0;36m#\033[m"
echo -e "\033[0;36m#===================================================#\033[m"
    echo ""
    echo -e "\033[0;36m[01]\033[m | Install SlowDNS SSH"
    echo -e "\033[0;36m[02]\033[m | Install SlowDNS SSL"
    echo -e "\033[0;36m[03]\033[m | Install SlowDNS DROPBEAR"
    echo -e "\033[0;36m[04]\033[m | Install SlowDNS SOCKS"
    echo -e "\033[0;36m[05]\033[m | See information"
    echo -e "\033[0;36m[06]\033[m | Start SlowDNS"
    echo -e "\033[0;36m[07]\033[m | RESTART SlowDNS"
    echo -e "\033[0;36m[08]\033[m | STOP SlowDNS"
    echo -e "\033[0;36m[09]\033[m | Remove SlowDNS"
    echo -e "\033[0;36m[10]\033[m | Update/Reinstall"
    echo -e "\033[0;36m[11]\033[m | Remove Script"
    echo -e "\033[0;36m[00]\033[m | EXIT"
    echo ""
    echo -ne "\033[0;36mWhat do you want to do?:\0033[m " && read option
    case $option in
    1) Option1 ;;
    2) Option2 ;;
    3) Option3 ;;
    4) Option4 ;;
    5) Option5 ;;
    6) Option6 ;;
    7) Option7 ;;
    8) Option8 ;;
    9) Option9 ;;
    10) Option10 ;;
    11) Option11 ;;
    0) Sair ;;
    *) "Invalid option" ; echo ; slowdns ;;
    esac
    }

Option1 () {
    clear
    bash /etc/slowdns/slowdns-ssh
}

Option2 () {
    clear
    bash /etc/slowdns/slowdns-ssl
}

Option3 () {
    clear
    bash /etc/slowdns/slowdns-drop
}

Option4 () {
    clear
    bash /etc/slowdns/slowdns-socks
}


Option5 () {
    clear
    bash /etc/slowdns/slowdns-info
}

Option6 () {
    clear
    bash /etc/slowdns/startdns
}

Option7 () {
    clear
    bash /etc/slowdns/restartdns
}

Option8 () {
    clear
    bash /etc/slowdns/stopdns
}

Option9 () {
     clear
    bash /etc/slowdns/stopdns
    bash /etc/slowdns/remove-slow
}

Option10 () {
    clear
    wget https://raw.githubusercontent.com/khaledagn/DNS-AGN/main/update
    chmod +x update
    bash update
}

Option11 () {
     clear
    bash /etc/slowdns/remove-slow
    echo -e "\033[0;31mSlowDNS Manager Uninstalled!\033[0m"
    sleep 2
    rm /bin/slowdns
}

Sair() {
    clear
    exit
}
clear
slowdns
