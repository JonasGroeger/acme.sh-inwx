# acme.sh-inwx

This is a plugin to make the DNS-01 work with [inwx.de](inwx.de) and [acme.sh](https://github.com/Neilpang/acme.sh).

## Installation

    git clone https://github.com/JonasGroeger/acme.sh-inwx.de.git
    cd acme.sh-inwx.de.git
    cp config.py.example config.py
    vim config.py
    ln -s "$(readlink -f dns_inwx.sh)" "PATH_TO_ACME_SH_DNSAPI_FOLDER/dns_inwx.sh"

## Usage

    ./acme.sh --issue --dns dns_inwx -d some.awesome.example.com

## Note

This is a rewrite of [Christians version](https://github.com/perryflynn/acme.sh-inwx).
