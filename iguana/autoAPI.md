


dpow API
===
need to create help/dpow.md file

## method: pending

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"pending\",\"fiat\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/pending?fiat={string}
```

field | value type | Description
--------- | ------- | -----------
fiat | string | no help info

## method: notarychains

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"notarychains\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/notarychains
```

field | value type | Description
--------- | ------- | -----------

## method: active

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"active\",\"maskhex\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/active?maskhex={string}
```

field | value type | Description
--------- | ------- | -----------
maskhex | string | no help info

## method: ratify

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"ratify\",\"minsigs\":\"{int}\",\"timestamp\":\"{int}\",\"ratified\":\"{array}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/ratify?minsigs={int}&timestamp={int}&ratified={array}
```

field | value type | Description
--------- | ------- | -----------
minsigs | int | no help info
timestamp | int | no help info
ratified | array | no help info

## method: cancelratify

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"cancelratify\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/cancelratify
```

field | value type | Description
--------- | ------- | -----------

## method: bindaddr

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"bindaddr\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/bindaddr?ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
ipaddr | string | no help info

## method: fundnotaries

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dpow\",\"method\":\"fundnotaries\",\"symbol\":\"{string}\",\"numblocks\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dpow/fundnotaries?symbol={string}&numblocks={int}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
numblocks | int | no help info

passthru API
===
need to create help/passthru.md file

## method: paxfiats

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"passthru\",\"method\":\"paxfiats\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/passthru/paxfiats
```

field | value type | Description
--------- | ------- | -----------

dex API
===
need to create help/dex.md file

## method: send

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"send\",\"hex\":\"{string}\",\"handler\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/send?hex={string}&handler={string}
```

field | value type | Description
--------- | ------- | -----------
hex | string | no help info
handler | string | no help info

## method: gettransaction

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"gettransaction\",\"txid\":\"{hash}\",\"symbol\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/gettransaction?txid={hash}&symbol={str}
```

field | value type | Description
--------- | ------- | -----------
txid | hash | no help info
symbol | str | no help info

## method: getinfo

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"getinfo\",\"symbol\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/getinfo?symbol={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info

## method: getnotaries

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"getnotaries\",\"symbol\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/getnotaries?symbol={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info

## method: alladdresses

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"alladdresses\",\"symbol\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/alladdresses?symbol={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info

## method: getbestblockhash

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"getbestblockhash\",\"symbol\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/getbestblockhash?symbol={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info

## method: getblockhash

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"getblockhash\",\"symbol\":\"{string}\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/getblockhash?symbol={string}&height={int}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
height | int | no help info

## method: getblock

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"getblock\",\"hash\":\"{hash}\",\"symbol\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/getblock?hash={hash}&symbol={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
symbol | str | no help info

## method: sendrawtransaction

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"sendrawtransaction\",\"symbol\":\"{string}\",\"signedtx\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/sendrawtransaction?symbol={string}&signedtx={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
signedtx | string | no help info

## method: gettxout

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"gettxout\",\"txid\":\"{hash}\",\"symbol\":\"{str}\",\"vout\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/gettxout?txid={hash}&symbol={str}&vout={int}
```

field | value type | Description
--------- | ------- | -----------
txid | hash | no help info
symbol | str | no help info
vout | int | no help info

## method: importaddress

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"importaddress\",\"symbol\":\"{string}\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/importaddress?symbol={string}&address={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
address | string | no help info

## method: validateaddress

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"validateaddress\",\"symbol\":\"{string}\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/validateaddress?symbol={string}&address={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
address | string | no help info

## method: listunspent

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"listunspent\",\"symbol\":\"{string}\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/listunspent?symbol={string}&address={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
address | string | no help info

## method: listtransactions

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"dex\",\"method\":\"listtransactions\",\"symbol\":\"{string}\",\"address\":\"{string}\",\"count\":\"{float}\",\"skip\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/dex/listtransactions?symbol={string}&address={string}&count={float}&skip={float}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
address | string | no help info
count | float | no help info
skip | float | no help info

zcash API
===
need to create help/zcash.md file

## method: passthru

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"zcash\",\"method\":\"passthru\",\"function\":\"{string}\",\"hex\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/zcash/passthru?function={string}&hex={string}
```

field | value type | Description
--------- | ------- | -----------
function | string | no help info
hex | string | no help info

komodo API
===
need to create help/komodo.md file

## method: passthru

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"komodo\",\"method\":\"passthru\",\"function\":\"{string}\",\"hex\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/komodo/passthru?function={string}&hex={string}
```

field | value type | Description
--------- | ------- | -----------
function | string | no help info
hex | string | no help info

pax API
===
need to create help/pax.md file

## method: start

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"pax\",\"method\":\"start\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/pax/start
```

field | value type | Description
--------- | ------- | -----------

tradebot API
===
need to create help/tradebot.md file

## method: liquidity

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"liquidity\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"targetcoin\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/liquidity?hash={hash}&vals={array}&targetcoin={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
targetcoin | str | no help info

## method: amlp

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"amlp\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/amlp
```

field | value type | Description
--------- | ------- | -----------

## method: notlp

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"notlp\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/notlp
```

field | value type | Description
--------- | ------- | -----------

## method: gensvm

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"gensvm\",\"base\":\"{string}\",\"rel\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/gensvm?base={string}&rel={string}
```

field | value type | Description
--------- | ------- | -----------
base | string | no help info
rel | string | no help info

## method: openliquidity

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"openliquidity\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/openliquidity
```

field | value type | Description
--------- | ------- | -----------

InstantDEX API
===
need to create help/InstantDEX.md file

## method: allcoins

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"allcoins\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/allcoins
```

field | value type | Description
--------- | ------- | -----------

## method: available

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"available\",\"source\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/available?source={string}
```

field | value type | Description
--------- | ------- | -----------
source | string | no help info

## method: request

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"request\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/request?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: incoming

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"incoming\",\"requestid\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/incoming?requestid={int}
```

field | value type | Description
--------- | ------- | -----------
requestid | int | no help info

## method: automatched

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"automatched\",\"requestid\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/automatched?requestid={int}
```

field | value type | Description
--------- | ------- | -----------
requestid | int | no help info

## method: accept

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"accept\",\"requestid\":\"{int}\",\"quoteid\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/accept?requestid={int}&quoteid={int}
```

field | value type | Description
--------- | ------- | -----------
requestid | int | no help info
quoteid | int | no help info

basilisk API
===
need to create help/basilisk.md file

## method: genesis_opreturn

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"genesis_opreturn\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/genesis_opreturn?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: history

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"history\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/history?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: paxfiats

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"paxfiats\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/paxfiats
```

field | value type | Description
--------- | ------- | -----------

## method: balances

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"balances\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/balances?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: value

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"value\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/value?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: rawtx

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"rawtx\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/rawtx?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: getmessage

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"getmessage\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/getmessage?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: sendmessage

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"sendmessage\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/sendmessage?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: geckoheaders

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"geckoheaders\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/geckoheaders?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: geckoblock

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"geckoblock\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/geckoblock?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: geckotx

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"geckotx\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/geckotx?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: geckoget

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"geckoget\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/geckoget?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: addrelay

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"addrelay\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/addrelay?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: dispatch

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"dispatch\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/dispatch?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: publish

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"publish\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/publish?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: subscribe

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"subscribe\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/subscribe?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: forward

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"forward\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/forward?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

## method: mailbox

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"basilisk\",\"method\":\"mailbox\",\"hash\":\"{hash}\",\"vals\":\"{array}\",\"hexstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/basilisk/mailbox?hash={hash}&vals={array}&hexstr={str}
```

field | value type | Description
--------- | ------- | -----------
hash | hash | no help info
vals | array | no help info
hexstr | str | no help info

bitcoinrpc API
===
need to create help/bitcoinrpc.md file

## method: getinfo

The getinfo RPC prints various information about the node and the network. 

 Parameters: none 

 Result—information about the node and network.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getinfo\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getinfo
```

field | value type | Description
--------- | ------- | -----------

## method: getblockcount

The getblockcount RPC returns the number of blocks in the local best block chain. 

 Parameters: none 

 Result—the number of blocks in the local best block chain.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getblockcount\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getblockcount
```

field | value type | Description
--------- | ------- | -----------

## method: getdifficulty

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getdifficulty\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getdifficulty
```

field | value type | Description
--------- | ------- | -----------

## method: getbestblockhash

The getbestblockhash RPC returns the header hash of the most recent block on the best block chain. 

 Parameters: none 

 Result—hash of the tip from the best block chain.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getbestblockhash\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getbestblockhash
```

field | value type | Description
--------- | ------- | -----------

## method: getblockhash

The getblockhash RPC returns the header hash of a block at the given height in the local best block chain. 

 Parameter—a block height. 

 Result—the block header hash. 


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getblockhash\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getblockhash?height={int}
```

field | value type | Description
--------- | ------- | -----------
height | int | A block height.

## method: getblock

The getblock RPC gets a block with a particular header hash from the local block database either as a JSON object or as a serialized block. 

 Parameter #1—header hash. 

 Parameter #2—JSON or hex output. 

 Result (if verbose was 0/hex)—a serialized block 

 Result (if verbose was 1/json or omitted)—a JSON block. 

> Command Output Response:

```
{
  "hash":"hash, (string) the block hash (same as provided)",
  "confirmations": " n, (numeric) The number of confirmations or -1 if the block is not on the main chain",
  "size": " n,(numeric) The block size",
  "height": "n, (numeric) The block height or index",
  "version": " n, (numeric) The block version",
 "merkleroot" : "xxxx, (string) The merkle root",
  "tx" : [
            "transactionid"    " The transaction id -(string array of transactionis IDs)     ,..." ],
  "time" : "ttt, (numeric) The block time in seconds since epoch (Jan 1 1970 GMT)",
  "mediantime" : "ttt,    (numeric) The median block time in seconds since epoch (Jan 1 1970 GMT)",
  "nonce" : "n, (numeric) The nonce",
  "bits" : "1d00ffff, (string) The bits",
  "difficulty" : "x.xxx,  (numeric) The difficulty",
  "chainwork" : "xxxx, (string) Expected number of hashes required to produce the chain up to this block (in hex)",
  "previousblockhash" : "hash,  (string) The hash of the previous block",
  "nextblockhash" : "hash, (string) The hash of the next block"

}
```



> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getblock\",\"blockhash\":\"{hash}\",\"verbose\":\"{int}\",\"remoteonly\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getblock?blockhash={hash}&verbose={int}&remoteonly={int}
```

field | value type | Description
--------- | ------- | -----------
blockhash | hash | The hash of the header of the block to get, encoded as hex in RPC byte order.
verbose | int | Get the resultant block in serialized block format or decoded JSON Object format.
remoteonly | int | Whether to include remote block in output or not.

## method: getrawtransaction

The getrawtransaction RPC gets a hex-encoded serialized transaction or a JSON object describing the transaction. By default, Bitcoin Core only stores complete transaction data for UTXOs and your own transactions, so the RPC may fail on historic transactions unless you use the non-default txindex=1 in your Bitcoin Core startup settings. 

 Parameter #1—the TXID of the transaction to get. 

 Parameter #2—whether to get the serialized or decoded transaction. 

 Result (if transaction not found)—null. 


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getrawtransaction\",\"txid\":\"{hash}\",\"verbose\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getrawtransaction?txid={hash}&verbose={int}
```

field | value type | Description
--------- | ------- | -----------
txid | hash |  The TXID of the transaction to get, encoded as hex in RPC byte order.
verbose | int | whether to get the serialized or decoded transaction.

## method: gettransaction

The gettransaction RPC gets detailed information about an in-wallet transaction.

 Parameter #1—a transaction identifier (TXID). 

 Result—a description of the transaction.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"gettransaction\",\"txid\":\"{hash}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/gettransaction?txid={hash}
```

field | value type | Description
--------- | ------- | -----------
txid | hash | The TXID of the transaction to get details about. The TXID must be encoded as hex in RPC byte order.

## method: gettxout

The gettxout RPC returns details about a transaction output. Only unspent transaction outputs (UTXOs) are guaranteed to be available. 

 Parameter #1—the TXID of the output to get. 

 Parameter #2—the output index number (vout) of the output to get. 

 Parameter #3—whether to display unconfirmed outputs from the memory pool. 

 Result—a description of the output.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"gettxout\",\"txid\":\"{hash}\",\"vout\":\"{int}\",\"mempool\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/gettxout?txid={hash}&vout={int}&mempool={int}
```

field | value type | Description
--------- | ------- | -----------
txid | hash | The TXID of the transaction containing the output to get, encoded as hex in RPC byte order.
vout | int | The output index number (vout) of the output within the transaction; the first output in a transaction is vout 0.
mempool | int | Set to 1 to display unconfirmed outputs from the memory pool; set to 0 (the default) to only display outputs from confirmed transactions.

## method: listunspent

The listunspent RPC returns an array of unspent transaction outputs belonging to this wallet. Note: as of Bitcoin Core 0.10.0, outputs affecting watch-only addresses will be returned. 

 Parameter #1—the minimum number of confirmations an output must have. 

 Parameter #2—the maximum number of confirmations an output may have. 

 Parameter #3—the addresses an output must pay. 

 Result—the list of unspent outputs.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listunspent\",\"minconf\":\"{int}\",\"maxconf\":\"{int}\",\"array\":\"{array}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listunspent?minconf={int}&maxconf={int}&array={array}
```

field | value type | Description
--------- | ------- | -----------
minconf | int | The minimum number of confirmations the transaction containing an output must have in order to be returned. Use 0 to return outputs from unconfirmed transactions. Default is 1.
maxconf | int | The maximum number of confirmations the transaction containing an output may have in order to be returned. Default is 9999999 (~10 million).
array | array | A P2PKH or P2SH address.

## method: decodescript

The decodescript RPC decodes a hex-encoded P2SH redeem script. 

 Parameter #1—a hex-encoded redeem script. 

 Result—the decoded script.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"decodescript\",\"scriptstr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/decodescript?scriptstr={string}
```

field | value type | Description
--------- | ------- | -----------
scriptstr | string | hex-encoded redeem script.

## method: decoderawtransaction

The decoderawtransaction RPC decodes a serialized transaction hex string into a JSON object describing the transaction. 

 Parameter #1—serialized transaction in hex. 

 Result—the decoded transaction.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"decoderawtransaction\",\"rawtx\":\"{string}\",\"suppress\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/decoderawtransaction?rawtx={string}&suppress={int}
```

field | value type | Description
--------- | ------- | -----------
rawtx | string | The transaction to decode in serialized transaction format.
suppress | int | no help info

## method: validaterawtransaction

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"validaterawtransaction\",\"rawtx\":\"{string}\",\"suppress\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/validaterawtransaction?rawtx={string}&suppress={int}
```

field | value type | Description
--------- | ------- | -----------
rawtx | string | no help info
suppress | int | no help info

## method: createrawtransaction

The createrawtransaction RPC creates an unsigned serialized transaction that spends a previous output to a new output with a P2PKH or P2SH address. The transaction is not stored in the wallet or transmitted to the network. 

 Parameter #1—references to previous outputs. 

 Parameter #2—P2PKH or P2SH addresses and amounts. 

 Result—the unsigned raw transaction in hex.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"createrawtransaction\",\"vins\":\"{array}\",\"vouts\":\"{object}\",\"locktime\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/createrawtransaction?vins={array}&vouts={object}&locktime={int}
```

field | value type | Description
--------- | ------- | -----------
vins | array | 1). The TXID of the outpoint encoded as hex in RPC byte order. 2). The output index number (vout) of the outpoint; the first output in a transaction is index 0.
vouts | object | A key/value pair with the address to pay as a string (key) and the amount to pay that address (value) in bitcoins.
locktime | int | Raw locktime, Non-0 value also locktime-activates inputs.

## method: validatepubkey

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"validatepubkey\",\"pubkey\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/validatepubkey?pubkey={string}
```

field | value type | Description
--------- | ------- | -----------
pubkey | string | no help info

## method: validateaddress

The validateaddress RPC accepts a block, verifies it is a valid addition to the block chain, and broadcasts it to the network. 

 Parameter #1—a P2PKH or P2SH address. 

 Result—information about the address.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"validateaddress\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/validateaddress?address={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | A single public bitcoin address to be validated.

## method: walletlock

The walletlock RPC prints various information about the node and the network. It Removes the wallet encryption key from memory, locking the wallet. You will need to call walletpassphrase again before being able to call any methods which require the wallet to be unlocked. 

 Parameters: none 

 Result—null on success. 


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"walletlock\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/walletlock
```

field | value type | Description
--------- | ------- | -----------

## method: walletpassphrase

The walletpassphrase RPC stores the wallet decryption key in memory for the indicated number of seconds. Issuing the walletpassphrase command while the wallet is already unlocked will set a new unlock time that overrides the old one. 

 Parameter #1—the passphrase. 

 Parameter #2—the number of seconds to leave the wallet unlocked. 

 Result—null on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"walletpassphrase\",\"password\":\"{string}\",\"permanentfile\":\"{string}\",\"timeout\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/walletpassphrase?password={string}&permanentfile={string}&timeout={int}
```

field | value type | Description
--------- | ------- | -----------
password | string | The passphrase that unlocks this wallet.
permanentfile | string | put in helpful info for field1
timeout | int |  The number of seconds after which the decryption key will be automatically deleted from memory. 600 = 10 minutes.

## method: encryptwallet

The encryptwallet RPC encrypts the wallet with a passphrase. This is only to enable encryption for the first time. After encryption is enabled, you will need to enter the passphrase to use private keys. 

 Parameter #1—a passphrase. 

 Result—a notice (with program shutdown on success).


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"encryptwallet\",\"passphrase\":\"{string}\",\"password\":\"{string}\",\"permanentfile\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/encryptwallet?passphrase={string}&password={string}&permanentfile={string}
```

field | value type | Description
--------- | ------- | -----------
passphrase | string | The passphrase to use for the encrypted wallet. Must be at least one character.
password | string | no help info
permanentfile | string | no help info

## method: walletpassphrasechange

The walletpassphrasechange RPC changes the wallet passphrase from ‘old passphrase’ to ‘new passphrase’.

 Parameter #1—the current passphrase. 

 Parameter #2—the new passphrase. 

 Result—null on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"walletpassphrasechange\",\"oldpassword\":\"{string}\",\"newpassword\":\"{string}\",\"oldpermanentfile\":\"{string}\",\"permanentfile\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/walletpassphrasechange?oldpassword={string}&newpassword={string}&oldpermanentfile={string}&permanentfile={string}
```

field | value type | Description
--------- | ------- | -----------
oldpassword | string | The current wallet passphrase.
newpassword | string | The new wallet passphrase.
oldpermanentfile | string | no help info
permanentfile | string | no help info

## method: dumpwallet

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet.The dumpwallet RPC creates or overwrites a file with all wallet keys in a human-readable format. 

 Parameter #1—a filename. 

 Result—null or error.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"dumpwallet\",\"filename\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/dumpwallet?filename={string}
```

field | value type | Description
--------- | ------- | -----------
filename | string | The file in which the wallet dump will be placed. May be prefaced by an absolute file path. An existing file with that name will be overwritten.

## method: backupwallet

Requires wallet support. The backupwallet RPC safely copies wallet.dat to the specified file, which can be a directory or a path with filename. 

 Parameter #1—destination directory or filename. 

 Result—null or error.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"backupwallet\",\"filename\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/backupwallet?filename={string}
```

field | value type | Description
--------- | ------- | -----------
filename | string | A filename or directory name. If a filename, it will be created or overwritten. If a directory name, the file wallet.dat will be created or overwritten within that directory.

## method: importwallet

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet. The importwallet RPC imports private keys from a file in wallet dump file format (see the dumpwallet RPC). These keys will be added to the keys currently in the wallet. This call may need to rescan all or parts of the block chain for transactions affecting the newly-added keys, which may take several minutes. 

 Parameter #1—the file to import. 

 Result—null on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"importwallet\",\"filename\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/importwallet?filename={string}
```

field | value type | Description
--------- | ------- | -----------
filename | string | The file to import. The path is relative to Bitcoin Core’s working directory.

## method: getnewaddress

Requires wallet support. The getnewaddress RPC returns a new Bitcoin address for receiving payments. If an account is specified, payments received with the address will be credited to that account. 

 Parameter #1—an account name. 

 Result—a bitcoin address never previously returned.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getnewaddress\",\"account\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getnewaddress?account={string}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of the account to put the address in. The default is the default account, an empty string (“”).

## method: importprivkey

Requires wallet support. Wallet must be unlocked.The importprivkey RPC adds a private key to your wallet. The key should be formatted in the wallet import format created by the dumpprivkey RPC. 

 Parameter #1—the private key to import. 

 Parameter #2—the account into which the key should be placed. 

 Parameter #3—whether to rescan the block chain. 

 Result—null on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"importprivkey\",\"wif\":\"{string}\",\"account\":\"{string}\",\"rescan\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/importprivkey?wif={string}&account={string}&rescan={int}
```

field | value type | Description
--------- | ------- | -----------
wif | string | The private key to import into the wallet encoded in base58check using wallet import format (WIF).
account | string | The name of an account to which transactions involving the key should be assigned. The default is the default account, an empty string (“”).
rescan | int | Set to 1 (the default) to rescan the entire local block database for transactions affecting any address or pubkey script in the wallet (including transaction affecting the newly-added address for this private key). Set to 0 to not rescan the block database (rescanning can be performed at any time by restarting Bitcoin Core with the -rescan command-line argument). Rescanning may take several minutes. Notes: if the address for this key is already in the wallet, the block database will not be rescanned even if this parameter is set.

## method: dumpprivkey

The dumpprivkey RPC returns the wallet-import-format (WIP) private key corresponding to an address. (But does not remove it from the wallet). 

 Parameter #1—the address corresponding to the private key to get. 

 Result—the private key.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"dumpprivkey\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/dumpprivkey?address={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | The P2PKH address corresponding to the private key you want returned. Must be an address corresponding to a private key in this wallet.

## method: listtransactions

The listtransactions RPC returns the most recent transactions that affect the wallet. 

 Parameter #1—an account name to get transactions from. 

 Parameter #2—the number of transactions to get. 

 Parameter #3—the number of transactions to skip. 

 Parameter #4—whether to include watch-only addresses in details and calculations. 

 Result—payment details.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listtransactions\",\"account\":\"{string}\",\"count\":\"{int}\",\"skip\":\"{int}\",\"includewatchonly\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listtransactions?account={string}&count={int}&skip={int}&includewatchonly={int}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of an account to get transactinos from. Use an empty string (“”) to get transactions for the default account. Default is * to get transactions for all accounts.
count | int | The number of the most recent transactions to list. Default is 10. Note: An artificial limit of 1,000 transactions is imposed by Chain Query's code.
skip | int | The number of the most recent transactions which should not be returned. Allows for pagination of results. Default is 0.
includewatchonly | int | If set to 0, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 1 (the default), treat watch-only addresses as if they didn’t belong to this wallet.

## method: listreceivedbyaddress

The listreceivedbyaddress RPC lists the total number of bitcoins received by each address. 

 Parameter #1—the minimum number of confirmations a transaction must have to be counted. 

 Parameter #2—whether to include empty accounts. 

 Parameter #3—whether to include watch-only addresses in results. 

 Result—addresses, account names, balances, and minimum confirmations.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listreceivedbyaddress\",\"minconf\":\"{int}\",\"includeempty\":\"{int}\",\"flag\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listreceivedbyaddress?minconf={int}&includeempty={int}&flag={int}
```

field | value type | Description
--------- | ------- | -----------
minconf | int | The minimum number of confirmations an externally-generated transaction must have before it is counted towards the balance. Transactions generated by this node are counted immediately. Typically, externally-generated transactions are payments to this wallet and transactions generated by this node are payments to other wallets. Use 0 to count unconfirmed transactions. Default is 1.
includeempty | int | Set to 1 to display accounts which have never received a payment. Set to 0 (the default) to only include accounts which have received a payment. Any account which has received a payment will be displayed even if its current balance is 0.
flag | int | If set to 1, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 0 (the default), treat watch-only addresses as if they didn’t belong to this wallet.

## method: listreceivedbyaccount

The listreceivedbyaccount RPC lists lists the total number of bitcoins received by each account. 

 Parameter #1—the minimum number of confirmations a transaction must have to be counted. 

 Parameter #2—whether to include empty accounts. 

 Parameter #3—whether to include watch-only addresses in results. 

 Result—account names, balances, and minimum confirmations.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listreceivedbyaccount\",\"confirmations\":\"{int}\",\"includeempty\":\"{int}\",\"watchonly\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listreceivedbyaccount?confirmations={int}&includeempty={int}&watchonly={int}
```

field | value type | Description
--------- | ------- | -----------
confirmations | int | The minimum number of confirmations an externally-generated transaction must have before it is counted towards the balance. Transactions generated by this node are counted immediately. Typically, externally-generated transactions are payments to this wallet and transactions generated by this node are payments to other wallets. Use 0 to count unconfirmed transactions. Default is 1.
includeempty | int | Set to 1 to display accounts which have never received a payment. Set to 0 (the default) to only include accounts which have received a payment. Any account which has received a payment will be displayed even if its current balance is 0.
watchonly | int | If set to 1, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 0 (the default), treat watch-only addresses as if they didn’t belong to this wallet.

## method: listaccounts

The listaccounts RPC lists accounts and their balances. 

 Parameter #1—the minimum number of confirmations a transaction must have. 

 Parameter #2—whether to include watch-only addresses in results. 

 Result—a list of accounts and their balances.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listaccounts\",\"minconf\":\"{int}\",\"includewatchonly\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listaccounts?minconf={int}&includewatchonly={int}
```

field | value type | Description
--------- | ------- | -----------
minconf | int | The minimum number of confirmations an externally-generated transaction must have before it is counted towards the balance. Transactions generated by this node are counted immediately. Typically, externally-generated transactions are payments to this wallet and transactions generated by this node are payments to other wallets. Use 0 to count unconfirmed transactions. Default is 1.
includewatchonly | int | If set to 1, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 0 (the default), treat watch-only addresses as if they didn’t belong to this wallet.

## method: listaddressgroupings

The listaddressgroupings RPC lists groups of addresses that may have had their common ownership made public by common use as inputs in the same transaction or from being used as change from a previous transaction. 

 Parameters: none 

 Result—an array of arrays describing the groupings.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listaddressgroupings\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listaddressgroupings
```

field | value type | Description
--------- | ------- | -----------

## method: getreceivedbyaddress

The getreceivedbyaddress RPC returns the total amount received by the specified address in transactions with the specified number of confirmations. It does not count coinbase transactions. 

 Parameter #1—the address. 

 Parameter #2—the minimum number of confirmations.

 Result—the number of bitcoins received.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getreceivedbyaddress\",\"address\":\"{string}\",\"minconf\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getreceivedbyaddress?address={string}&minconf={int}
```

field | value type | Description
--------- | ------- | -----------
address | string | The address whose transactions should be tallied.
minconf | int | The minimum number of confirmations an externally-generated transaction must have before it is counted towards the balance. Transactions generated by this node are counted immediately. Typically, externally-generated transactions are payments to this wallet and transactions generated by this node are payments to other wallets. Use 0 to count unconfirmed transactions. Default is 1.

## method: getreceivedbyaccount

The getreceivedbyaccount RPC returns the total amount received by addresses in a particular account from transactions with the specified number of confirmations. It does not count coinbase transactions. 

 Parameter #1—the account name. 

 Parameter #2—whether to include empty accounts. 

 Result—the number of bitcoins received.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getreceivedbyaccount\",\"account\":\"{string}\",\"includeempty\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getreceivedbyaccount?account={string}&includeempty={int}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of an account.
includeempty | int | Set to 1 to display accounts which have never received a payment. Set to 0 (the default) to only include accounts which have received a payment. Any account which has received a payment will be displayed even if its current balance is 0.

## method: getbalance

The getbalance RPC gets the balance in decimal bitcoins across all accounts or for a particular account. 

 Parameter #1—an account name. 

 Parameter#2—the minimum number of confirmation. 

 Parameter #3—whether to include watch-only addresses. 

 Parameter #4—last height. 

 Result—the balance in bitcoins.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getbalance\",\"account\":\"{string}\",\"confirmations\":\"{int}\",\"includeempty\":\"{int}\",\"lastheight\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getbalance?account={string}&confirmations={int}&includeempty={int}&lastheight={int}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of an account to get the balance for. An empty string (“”) is the default account (default). The string * will get the balance for all accounts.
confirmations | int | The minimum number of confirmations an externally-generated transaction must have before it is counted towards the balance. Transactions generated by this node are counted immediately. Typically, externally-generated transactions are payments to this wallet and transactions generated by this node are payments to other wallets. Use 0 to count unconfirmed transactions. Default is 1.
includeempty | int | set to 1, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 0 (the default), treat watch-only addresses as if they didn’t belong to this wallet.
lastheight | int | put in helpful info

## method: getaddressesbyaccount

The getaddressesbyaccount RPC returns a list of every address assigned to a particular account. 

 Parameter #1—the account name. 

 Result—a list of addresses.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getaddressesbyaccount\",\"account\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getaddressesbyaccount?account={string}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of an account.

## method: getaccount

The getaccount RPC returns the name of the account associated with the given address. 

 Parameter #1—a Bitcoin address. 

 Result—an account name.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getaccount\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getaccount?address={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | A P2PKH or P2SH Bitcoin address belonging either to a specific account or the default account (“”).

## method: getaccountaddress

The getaccountaddress RPC returns the current Bitcoin address for receiving payments to this account. If the account doesn’t exist, it creates both the account and a new address for receiving payment. Once a payment has been received to an address, future calls to this RPC for the same account will return a different address. 

 Parameter #1—an account name. 

 Result—a bitcoin address. 


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getaccountaddress\",\"account\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getaccountaddress?account={string}
```

field | value type | Description
--------- | ------- | -----------
account | string | The name of an account. Leave blank for the default account. If the account doesn’t exist, it will be created.

## method: setaccount

The setaccount RPC puts the specified address in the given account. 

 Parameter #1—a bitcoin address. 

 Parameter #2—an account. 

 Result—null if successful.Set to JSON null if the address was successfully placed in the account.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"setaccount\",\"address\":\"{string}\",\"account\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/setaccount?address={string}&account={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | The P2PKH or P2SH address to put in the account. Must already belong to the wallet.
account | string | The name of the account in which the address should be placed. May be the default account, an empty string (“”).

## method: createmultisig

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"createmultisig\",\"M\":\"{int}\",\"pubkeys\":\"{array}\",\"ignore\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/createmultisig?M={int}&pubkeys={array}&ignore={string}
```

field | value type | Description
--------- | ------- | -----------
M | int | no help info
pubkeys | array | no help info
ignore | string | no help info

## method: addmultisigaddress

The addmultisigaddress RPC adds a P2SH multisig address to the wallet. 

 Parameter #1—the number of signatures required. 

 Parameter #2—the full public keys, or addresses for known public keys. 

 Parameter #3—the account name. 

 Result—a P2SH address printed and stored in the wallet.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"addmultisigaddress\",\"M\":\"{int}\",\"pubkeys\":\"{array}\",\"account\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/addmultisigaddress?M={int}&pubkeys={array}&account={string}
```

field | value type | Description
--------- | ------- | -----------
M | int | The minimum (m) number of signatures required to spend this m-of-n multisig script.
pubkeys | array | An array of strings with each string being a public key or address.
account | string | The account name in which the address should be stored. Default is the default account, “” (an empty string).

## method: settxfee

The settxfee RPC sets the transaction fee per kilobyte paid by transactions created by this wallet. 

 Parameter #1—the transaction fee amount per kilobyte. 

 Result: true on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"settxfee\",\"amount\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/settxfee?amount={float}
```

field | value type | Description
--------- | ------- | -----------
amount | float | The transaction fee to pay, in bitcoins, for each kilobyte of transaction data. Be careful setting the fee too low—your transactions may not be relayed or included in blocks.

## method: checkwallet

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"checkwallet\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/checkwallet
```

field | value type | Description
--------- | ------- | -----------

## method: repairwallet

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"repairwallet\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/repairwallet
```

field | value type | Description
--------- | ------- | -----------

## method: signrawtransaction

The signrawtransaction RPC signs a transaction in the serialized transaction format using private keys stored in the wallet or provided in the call.

 Parameter #1—the transaction to sign. 

 Parameter #2—unspent transaction output details. 

 Parameter #3—private keys for signing. 

 Parameter #4—signature hash type. 

 Result—the transaction with any signatures made.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"signrawtransaction\",\"rawtx\":\"{string}\",\"vins\":\"{array}\",\"privkeys\":\"{object}\",\"sighash\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/signrawtransaction?rawtx={string}&vins={array}&privkeys={object}&sighash={string}
```

field | value type | Description
--------- | ------- | -----------
rawtx | string | The transaction to sign as a serialized transaction.
vins | array | txid: The TXID of the transaction the output appeared in. The TXID must be encoded in hex in RPC byte order. vout: The index number of the output (vout) as it appeared in its transaction, with the first output being 0. scriptPubKey: The output’s pubkey script encoded as hex.
privkeys | object | A private key in base58check format to use to create a signature for this transaction.
sighash | string | The type of signature hash to use for all of the signatures performed. (You must use separate calls to the signrawtransaction RPC if you want to use different signature hash types for different signatures. The allowed values are: ALL, NONE, SINGLE, ALL|ANYONECANPAY, NONE|ANYONECANPAY, and SINGLE|ANYONECANPAY.

## method: signmessage

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet. The signmessage RPC signs a message with the private key of an address. 

 Parameter #1—the address corresponding to the private key to sign with. 

 Parameter #2—the message to sign. 

 Result—the message signature. 


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"signmessage\",\"address\":\"{string}\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/signmessage?address={string}&message={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | A P2PKH address whose private key belongs to this wallet.
message | string | The message to sign.

## method: verifymessage

The verifymessage RPC verifies a signed message. 

 Parameter #1—the address corresponding to the signing key. 

 Parameter #2—the signature. 

 Parameter #3—the message. 

 Result: true, false, or an error.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"verifymessage\",\"address\":\"{string}\",\"sig\":\"{string}\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/verifymessage?address={string}&sig={string}&message={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | The P2PKH address corresponding to the private key which made the signature. A P2PKH address is a hash of the public key corresponding to the private key which made the signature. When the ECDSA signature is checked, up to four possible ECDSA public keys will be reconstructed from from the signature; each key will be hashed and compared against the P2PKH address provided to see if any of them match. If there are no matches, signature validation will fail.
sig | string | The signature created by the signer encoded as base-64 (the format output by the signmessage RPC).
message | string | The message exactly as it was signed (e.g. no extra whitespace).

## method: sendrawtransaction

The sendrawtransaction RPC validates a transaction and broadcasts it to the peer-to-peer network. 

 Parameter #1—a serialized transaction to broadcast. 

 Parameter #2–whether to allow high fees. 

 Result—a TXID or error message.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"sendrawtransaction\",\"rawtx\":\"{string}\",\"allowhighfees\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/sendrawtransaction?rawtx={string}&allowhighfees={int}
```

field | value type | Description
--------- | ------- | -----------
rawtx | string | The serialized transaction to broadcast encoded as hex.
allowhighfees | int | Set to 1 to allow the transaction to pay a high transaction fee. Set to 0 (the default) to prevent Bitcoin Core from broadcasting the transaction if it includes a high fee. Transaction fees are the sum of the inputs minus the sum of the outputs, so this high fees check helps ensures user including a change address to return most of the difference back to themselves.

## method: sendfrom

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet. The sendfrom RPC spends an amount from a local account to a bitcoin address. 

 Parameter #1—from account. 

 Parameter #2—to address. 

 Parameter #3—amount to spend. 

 Parameter #4—minimum confirmations. 

 Parameter #5—a comment. 

 Parameter #6—a comment about who the payment was sent to. 

 Result—a TXID of the sent transaction.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"sendfrom\",\"fromaccount\":\"{string}\",\"toaddress\":\"{string}\",\"amount\":\"{float}\",\"minconf\":\"{int}\",\"comment\":\"{string}\",\"comment2\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/sendfrom?fromaccount={string}&toaddress={string}&amount={float}&minconf={int}&comment={string}&comment2={string}
```

field | value type | Description
--------- | ------- | -----------
fromaccount | string | The name of the account from which the bitcoins should be spent. Use an empty string (“”) for the default account.
toaddress | string | no help info
amount | float | The amount to spend in bitcoins. Bitcoin Core will ensure the account has sufficient bitcoins to pay this amount (but the transaction fee paid is not included in the calculation, so an account can spend a total of its balance plus the transaction fee).
minconf | int | The minimum number of confirmations an incoming transaction must have for its outputs to be credited to this account’s balance. Outgoing transactions are always counted, as are move transactions made with the move RPC. If an account doesn’t have a balance high enough to pay for this transaction, the payment will be rejected. Use 0 to spend unconfirmed incoming payments. Default is 1.
comment | string | A locally-stored (not broadcast) comment assigned to this transaction. Default is no comment.
comment2 | string | A locally-stored (not broadcast) comment assigned to this transaction. Meant to be used for describing who the payment was sent to. Default is no comment.

## method: sendmany

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet. The sendmany RPC creates and broadcasts a transaction which sends outputs to multiple addresses. 

 Parameter #1—from account. 

 Parameter #2—the addresses and amounts to pay. 

 Parameter #3—minimum confirmations. 

 Parameter #4—a comment. 

 Result—a TXID of the sent transaction.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"sendmany\",\"fromaccount\":\"{string}\",\"payments\":\"{array}\",\"minconf\":\"{int}\",\"comment\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/sendmany?fromaccount={string}&payments={array}&minconf={int}&comment={string}
```

field | value type | Description
--------- | ------- | -----------
fromaccount | string | The name of the account from which the bitcoins should be spent. Use an empty string (“”) for the default account. Bitcoin Core will ensure the account has sufficient bitcoins to pay the total amount in the outputs field described below (but the transaction fee paid is not included in the calculation, so an account can spend a total of its balance plus the transaction fee).
payments | array | An object containing key/value pairs corresponding to the addresses and amounts to pay.
minconf | int | The minimum number of confirmations an incoming transaction must have for its outputs to be credited to this account’s balance. Outgoing transactions are always counted, as are move transactions made with the move RPC. If an account doesn’t have a balance high enough to pay for this transaction, the payment will be rejected. Use 0 to spend unconfirmed incoming payments. Default is 1.
comment | string | A locally-stored (not broadcast) comment assigned to this transaction. Default is no comment.

## method: sendtoaddress

Requires wallet support. Requires an unlocked wallet or an unencrypted wallet.The sendtoaddress RPC spends an amount to a given address. 

 Parameter #1—to address. 

 Parameter #2—amount to spend. 

 Parameter #3—a comment. 

 Parameter #4—a comment about who the payment was sent to. 

 Result—a TXID of the sent transaction.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"sendtoaddress\",\"address\":\"{string}\",\"amount\":\"{float}\",\"comment\":\"{string}\",\"comment2\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/sendtoaddress?address={string}&amount={float}&comment={string}&comment2={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | A P2PKH or P2SH address to which the bitcoins should be sent.
amount | float | The amount to spent in bitcoins.
comment | string | A locally-stored (not broadcast) comment assigned to this transaction. Default is no comment.
comment2 | string | A locally-stored (not broadcast) comment assigned to this transaction. Meant to be used for describing who the payment was sent to. Default is no comment.

## method: lockunspent

Requires wallet support.The lockunspent RPC temporarily locks or unlocks specified transaction outputs. A locked transaction output will not be chosen by automatic coin selection when spending bitcoins. Locks are stored in memory only, so nodes start with zero locked outputs and the locked output list is always cleared when a node stops or fails.

 Parameter #1—whether to lock or unlock the outputs. 

 Parameter #2—the outputs to lock or unlock. 

 Result—true if successful.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"lockunspent\",\"flag\":\"{int}\",\"array\":\"{array}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/lockunspent?flag={int}&array={array}
```

field | value type | Description
--------- | ------- | -----------
flag | int | Set to 0 to lock the outputs specified in the following parameter. Set to 1 to unlock the outputs specified. If this is the only argument specified and it is set to true, all outputs will be unlocked; if it is the only argument and is set to false, there will be no change.
array | array | An array of outputs to lock or unlock.

## method: listlockunspent

Requires wallet support.The listlockunspent RPC returns a list of temporarily unspendable (locked) outputs. 

 Parameters: none. 

 Result—an array of locked outputs.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listlockunspent\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listlockunspent
```

field | value type | Description
--------- | ------- | -----------

## method: submitblock

The submitblock RPC accepts a block, verifies it is a valid addition to the block chain, and broadcasts it to the network. Extra parameters are ignored by Bitcoin Core but may be used by mining pools or other programs. Parameter #1—the new block in serialized block format as hex. 

 Result—null or error string.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"submitblock\",\"rawbytes\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/submitblock?rawbytes={string}
```

field | value type | Description
--------- | ------- | -----------
rawbytes | string | The full block to submit in serialized block format as hex.

## method: listsinceblock

The listsinceblock RPC gets all transactions affecting the wallet which have occurred since a particular block, plus the header hash of a block at a particular depth. 

 Parameter #1—a block header hash. 

 Parameter #2—the target confirmations for the lastblock field. 

 Parameter #3—whether to include watch-only addresses in details and calculations. 

 Result— An object containing an array of transactions and the lastblock field.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"listsinceblock\",\"blockhash\":\"{hash}\",\"target\":\"{int}\",\"flag\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/listsinceblock?blockhash={hash}&target={int}&flag={int}
```

field | value type | Description
--------- | ------- | -----------
blockhash | hash | The hash of a block header encoded as hex in RPC byte order. All transactions affecting the wallet which are not in that block or any earlier block will be returned, including unconfirmed transactions. Default is the hash of the genesis block, so all transactions affecting the wallet are returned by default.
target | int | Sets the lastblock field of the results to the header hash of a block with this many confirmations. This does not affect which transactions are returned. Default is 1, so the hash of the most recent block on the local best block chain is returned.
flag | int | f set to 1, include watch-only addresses in details and calculations as if they were regular addresses belonging to the wallet. If set to 0 (the default), treat watch-only addresses as if they didn’t belong to this wallet.

## method: gettxoutsetinfo

The gettxoutsetinfo RPC returns statistics about the confirmed unspent transaction output (UTXO) set. Note that this call may take some time and that it only counts outputs from confirmed transactions—it does not count outputs from the memory pool. 

 Parameters: none. 

 Result—statistics about the UTXO set.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"gettxoutsetinfo\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/gettxoutsetinfo
```

field | value type | Description
--------- | ------- | -----------

## method: getrawchangeaddress

Requires wallet support. The getrawchangeaddress RPC returns a new Bitcoin address for receiving change. This is for use with raw transactions, not normal use. 

 Parameters: none. 

 Result—a P2PKH address which can be used in raw transactions.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"getrawchangeaddress\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/getrawchangeaddress
```

field | value type | Description
--------- | ------- | -----------

## method: move

Requires wallet support.The move RPC moves a specified amount from one account in your wallet to another using an off-block-chain transaction. 

 Parameter #1—from account. 

 Parameter #2—to account. 

 Parameter #3—amount to move. 

 Parameter #4—an unused parameter.

 Parameter #5—a comment. 

 Result—true on success.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"bitcoinrpc\",\"method\":\"move\",\"fromaccount\":\"{string}\",\"toaccount\":\"{string}\",\"amount\":\"{float}\",\"minconf\":\"{int}\",\"comment\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/bitcoinrpc/move?fromaccount={string}&toaccount={string}&amount={float}&minconf={int}&comment={string}
```

field | value type | Description
--------- | ------- | -----------
fromaccount | string | The name of the account to move the funds from.
toaccount | string | The name of the account to move the funds to.
amount | float | The amount of bitcoins to move.
minconf | int | This parameter is no longer used. If parameter #5 needs to be specified, this can be any integer.
comment | string | A comment to assign to this move payment.

iguana API
===
need to create help/iguana.md file

## method: splitfunds

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"splitfunds\",\"satoshis\":\"{int}\",\"duplicates\":\"{int}\",\"sendflag\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/splitfunds?satoshis={int}&duplicates={int}&sendflag={int}
```

field | value type | Description
--------- | ------- | -----------
satoshis | int | no help info
duplicates | int | no help info
sendflag | int | no help info

## method: makekeypair

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"makekeypair\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/makekeypair
```

field | value type | Description
--------- | ------- | -----------

## method: rates

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"rates\",\"unused\":\"{int}\",\"quotes\":\"{array}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/rates?unused={int}&quotes={array}
```

field | value type | Description
--------- | ------- | -----------
unused | int | no help info
quotes | array | no help info

## method: rate

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"rate\",\"base\":\"{string}\",\"rel\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/rate?base={string}&rel={string}
```

field | value type | Description
--------- | ------- | -----------
base | string | no help info
rel | string | no help info

## method: prices

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"prices\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"period\":\"{int}\",\"start\":\"{int}\",\"end\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/prices?exchange={string}&base={string}&rel={string}&period={int}&start={int}&end={int}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
period | int | no help info
start | int | no help info
end | int | no help info

## method: snapshot

snapshot is passed in the symbol of the coin and the height for the snapshot, the height must be a multiple of bundle size and the utxoaddrs.<height> file must already exist in the DB/<symbol> folder. 

 It will if you have been maintaining a coin in RT mode. 

 The snapshot API just returns a complete set of { address, <amount> } in an array.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"snapshot\",\"symbol\":\"{string}\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/snapshot?symbol={string}&height={int}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | BTCD,BTC,LTC,DOGE,KMD,SYSCOIN...
height | int | multiple of bundlesize <bundlesize> is either 160, 500 or 2000(for zcash fork).

## method: dividends

The dividends API uses internally the snapshot API. It also specifies symbol and height, but there is also a vals object, which specifies how to process the snapshot array.


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"dividends\",\"height\":\"{int}\",\"vals\":\"{array}\",\"symbol\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/dividends?height={int}&vals={array}&symbol={string}
```

field | value type | Description
--------- | ------- | -----------
height | int | multiple of bundlesize is either 160, 500 or 2000(for zcash fork).
vals | array | It specifies how to process snapshot array{}
symbol | string | BTCD,BTC or any active coin

## method: passthru

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"passthru\",\"asset\":\"{string}\",\"function\":\"{string}\",\"hex\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/passthru?asset={string}&function={string}&hex={string}
```

field | value type | Description
--------- | ------- | -----------
asset | string | no help info
function | string | no help info
hex | string | no help info

## method: initfastfind

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"initfastfind\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/initfastfind?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: dpow

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"dpow\",\"symbol\":\"{string}\",\"pubkey\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/dpow?symbol={string}&pubkey={string}
```

field | value type | Description
--------- | ------- | -----------
symbol | string | no help info
pubkey | string | no help info

## method: peers

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"peers\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/peers?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: maxpeers

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"maxpeers\",\"activecoin\":\"{string}\",\"max\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/maxpeers?activecoin={string}&max={int}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
max | int | no help info

## method: getconnectioncount

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"getconnectioncount\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/getconnectioncount?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: addcoin

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"addcoin\",\"newcoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/addcoin?newcoin={string}
```

field | value type | Description
--------- | ------- | -----------
newcoin | string | no help info

## method: validate

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"validate\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/validate?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: removecoin

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"removecoin\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/removecoin?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: startcoin

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"startcoin\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/startcoin?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: pausecoin

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"pausecoin\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/pausecoin?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: stopcoin

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"stopcoin\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/stopcoin?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: addnode

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"addnode\",\"activecoin\":\"{string}\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/addnode?activecoin={string}&ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
ipaddr | string | no help info

## method: addnotary

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"addnotary\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/addnotary?ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
ipaddr | string | no help info

## method: persistent

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"persistent\",\"activecoin\":\"{string}\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/persistent?activecoin={string}&ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
ipaddr | string | no help info

## method: removenode

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"removenode\",\"activecoin\":\"{string}\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/removenode?activecoin={string}&ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
ipaddr | string | no help info

## method: oneshot

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"oneshot\",\"activecoin\":\"{string}\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/oneshot?activecoin={string}&ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
ipaddr | string | no help info

## method: nodestatus

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"nodestatus\",\"activecoin\":\"{string}\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/nodestatus?activecoin={string}&ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
ipaddr | string | no help info

## method: balance

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"balance\",\"activecoin\":\"{string}\",\"address\":\"{string}\",\"heightd\":\"{float}\",\"minconfd\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/balance?activecoin={string}&address={string}&heightd={float}&minconfd={float}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
address | string | no help info
heightd | float | no help info
minconfd | float | no help info

## method: spendmsig

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"spendmsig\",\"activecoin\":\"{string}\",\"vintxid\":\"{hash}\",\"vinvout\":\"{int}\",\"destaddress\":\"{string}\",\"destamount\":\"{float}\",\"destaddress2\":\"{string}\",\"destamount2\":\"{float}\",\"M\":\"{int}\",\"N\":\"{int}\",\"pubA\":\"{string}\",\"wifA\":\"{string}\",\"pubB\":\"{string}\",\"wifB\":\"{string}\",\"pubC\":\"{string}\",\"wifC\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/spendmsig?activecoin={string}&vintxid={hash}&vinvout={int}&destaddress={string}&destamount={float}&destaddress2={string}&destamount2={float}&M={int}&N={int}&pubA={string}&wifA={string}&pubB={string}&wifB={string}&pubC={string}&wifC={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
vintxid | hash | no help info
vinvout | int | no help info
destaddress | string | no help info
destamount | float | no help info
destaddress2 | string | no help info
destamount2 | float | no help info
M | int | no help info
N | int | no help info
pubA | string | no help info
wifA | string | no help info
pubB | string | no help info
wifB | string | no help info
pubC | string | no help info
wifC | string | no help info

## method: bundleaddresses

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"bundleaddresses\",\"activecoin\":\"{string}\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/bundleaddresses?activecoin={string}&height={int}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
height | int | no help info

## method: bundlehashes

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"bundlehashes\",\"activecoin\":\"{string}\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/bundlehashes?activecoin={string}&height={int}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
height | int | no help info

## method: PoSweights

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"PoSweights\",\"activecoin\":\"{string}\",\"height\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/PoSweights?activecoin={string}&height={int}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info
height | int | no help info

## method: stakers

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"iguana\",\"method\":\"stakers\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/iguana/stakers?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

InstantDEX API
===
need to create help/InstantDEX.md file

## method: buy

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"buy\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"price\":\"{float}\",\"volume\":\"{float}\",\"dotrade\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/buy?exchange={string}&base={string}&rel={string}&price={float}&volume={float}&dotrade={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
price | float | no help info
volume | float | no help info
dotrade | float | no help info

## method: sell

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"sell\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"price\":\"{float}\",\"volume\":\"{float}\",\"dotrade\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/sell?exchange={string}&base={string}&rel={string}&price={float}&volume={float}&dotrade={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
price | float | no help info
volume | float | no help info
dotrade | float | no help info

## method: withdraw

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"withdraw\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"destaddr\":\"{string}\",\"amount\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/withdraw?exchange={string}&base={string}&destaddr={string}&amount={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
destaddr | string | no help info
amount | float | no help info

## method: apikeypair

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"apikeypair\",\"exchange\":\"{string}\",\"apikey\":\"{string}\",\"apisecret\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/apikeypair?exchange={string}&apikey={string}&apisecret={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
apikey | string | no help info
apisecret | string | no help info

## method: setuserid

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"setuserid\",\"exchange\":\"{string}\",\"userid\":\"{string}\",\"tradepassword\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/setuserid?exchange={string}&userid={string}&tradepassword={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
userid | string | no help info
tradepassword | string | no help info

## method: balance

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"balance\",\"exchange\":\"{string}\",\"base\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/balance?exchange={string}&base={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info

## method: orderstatus

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"orderstatus\",\"exchange\":\"{string}\",\"orderid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/orderstatus?exchange={string}&orderid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
orderid | string | no help info

## method: cancelorder

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"cancelorder\",\"exchange\":\"{string}\",\"orderid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/cancelorder?exchange={string}&orderid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
orderid | string | no help info

## method: openorders

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"openorders\",\"exchange\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/openorders?exchange={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info

## method: tradehistory

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"tradehistory\",\"exchange\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/tradehistory?exchange={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info

## method: orderbook

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"orderbook\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"depth\":\"{int}\",\"allfields\":\"{int}\",\"ignore\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/orderbook?exchange={string}&base={string}&rel={string}&depth={int}&allfields={int}&ignore={int}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
depth | int | no help info
allfields | int | no help info
ignore | int | no help info

## method: pollgap

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"pollgap\",\"exchange\":\"{string}\",\"pollgap\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/pollgap?exchange={string}&pollgap={int}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
pollgap | int | no help info

## method: allexchanges

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"allexchanges\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/allexchanges
```

field | value type | Description
--------- | ------- | -----------

## method: allpairs

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"allpairs\",\"exchange\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/allpairs?exchange={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info

## method: supports

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"InstantDEX\",\"method\":\"supports\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/InstantDEX/supports?exchange={string}&base={string}&rel={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info

tradebot API
===
need to create help/tradebot.md file

## method: aveprice

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"aveprice\",\"comment\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"basevolume\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/aveprice?comment={string}&base={string}&rel={string}&basevolume={float}
```

field | value type | Description
--------- | ------- | -----------
comment | string | no help info
base | string | no help info
rel | string | no help info
basevolume | float | no help info

## method: monitor

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"monitor\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"commission\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/monitor?exchange={string}&base={string}&rel={string}&commission={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
commission | float | no help info

## method: monitorall

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"monitorall\",\"exchange\":\"{string}\",\"commission\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/monitorall?exchange={string}&commission={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
commission | float | no help info

## method: unmonitor

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"unmonitor\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/unmonitor?exchange={string}&base={string}&rel={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info

## method: accumulate

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"accumulate\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"price\":\"{float}\",\"volume\":\"{float}\",\"duration\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/accumulate?exchange={string}&base={string}&rel={string}&price={float}&volume={float}&duration={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
price | float | no help info
volume | float | no help info
duration | float | no help info

## method: divest

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"divest\",\"exchange\":\"{string}\",\"base\":\"{string}\",\"rel\":\"{string}\",\"price\":\"{float}\",\"volume\":\"{float}\",\"duration\":\"{float}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/divest?exchange={string}&base={string}&rel={string}&price={float}&volume={float}&duration={float}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
base | string | no help info
rel | string | no help info
price | float | no help info
volume | float | no help info
duration | float | no help info

## method: activebots

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"activebots\",\"exchange\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/activebots?exchange={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info

## method: status

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"status\",\"exchange\":\"{string}\",\"botid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/status?exchange={string}&botid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
botid | string | no help info

## method: pause

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"pause\",\"exchange\":\"{string}\",\"botid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/pause?exchange={string}&botid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
botid | string | no help info

## method: stop

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"stop\",\"exchange\":\"{string}\",\"botid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/stop?exchange={string}&botid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
botid | string | no help info

## method: resume

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"tradebot\",\"method\":\"resume\",\"exchange\":\"{string}\",\"botid\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/tradebot/resume?exchange={string}&botid={string}
```

field | value type | Description
--------- | ------- | -----------
exchange | string | no help info
botid | string | no help info

SuperNET API
===
need to create help/SuperNET.md file

## method: help

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"help\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/help
```

field | value type | Description
--------- | ------- | -----------

## method: utime2utc

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"utime2utc\",\"utime\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/utime2utc?utime={string}
```

field | value type | Description
--------- | ------- | -----------
utime | string | no help info

## method: utc2utime

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"utc2utime\",\"utc\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/utc2utime?utc={int}
```

field | value type | Description
--------- | ------- | -----------
utc | int | no help info

## method: getpeers

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"getpeers\",\"activecoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/getpeers?activecoin={string}
```

field | value type | Description
--------- | ------- | -----------
activecoin | string | no help info

## method: mypeers

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"mypeers\",\"supernet\":\"{array}\",\"rawpeers\":\"{array}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/mypeers?supernet={array}&rawpeers={array}
```

field | value type | Description
--------- | ------- | -----------
supernet | array | no help info
rawpeers | array | no help info

## method: stop

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"stop\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/stop
```

field | value type | Description
--------- | ------- | -----------

## method: saveconf

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"saveconf\",\"wallethash\":\"{hash}\",\"confjsonstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/saveconf?wallethash={hash}&confjsonstr={str}
```

field | value type | Description
--------- | ------- | -----------
wallethash | hash | no help info
confjsonstr | str | no help info

## method: layer

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"layer\",\"mypriv\":\"{hash}\",\"otherpubs\":\"{array}\",\"str\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/layer?mypriv={hash}&otherpubs={array}&str={str}
```

field | value type | Description
--------- | ------- | -----------
mypriv | hash | no help info
otherpubs | array | no help info
str | str | no help info

## method: bitcoinrpc

Set the coin  to use for bitcoin RPC calls. this will suffice in single coin environments. That is bitcoinrpc API just sets the coin to use for the bitcoin RPC api


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"bitcoinrpc\",\"setcoin\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/bitcoinrpc?setcoin={string}
```

field | value type | Description
--------- | ------- | -----------
setcoin | string | no help info

## method: myipaddr

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"myipaddr\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/myipaddr?ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
ipaddr | string | no help info

## method: setmyipaddr

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"setmyipaddr\",\"ipaddr\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/setmyipaddr?ipaddr={string}
```

field | value type | Description
--------- | ------- | -----------
ipaddr | string | no help info

## method: login

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"login\",\"handle\":\"{string}\",\"password\":\"{string}\",\"permanentfile\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/login?handle={string}&password={string}&permanentfile={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
handle | string | no help info
password | string | no help info
permanentfile | string | no help info
passphrase | string | no help info

## method: logout

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"logout\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/logout
```

field | value type | Description
--------- | ------- | -----------

## method: activehandle

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"activehandle\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/activehandle
```

field | value type | Description
--------- | ------- | -----------

## method: encryptjson

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"encryptjson\",\"password\":\"{string}\",\"permanentfile\":\"{string}\",\"payload\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/encryptjson?password={string}&permanentfile={string}&payload={string}
```

field | value type | Description
--------- | ------- | -----------
password | string | no help info
permanentfile | string | no help info
payload | string | no help info

## method: decryptjson

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"decryptjson\",\"password\":\"{string}\",\"permanentfile\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/decryptjson?password={string}&permanentfile={string}
```

field | value type | Description
--------- | ------- | -----------
password | string | no help info
permanentfile | string | no help info

## method: html

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"html\",\"agentform\":\"{string}\",\"htmlfile\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/html?agentform={string}&htmlfile={string}
```

field | value type | Description
--------- | ------- | -----------
agentform | string | no help info
htmlfile | string | no help info

## method: rosetta

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"rosetta\",\"passphrase\":\"{string}\",\"pin\":\"{string}\",\"showprivkey\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/rosetta?passphrase={string}&pin={string}&showprivkey={string}
```

field | value type | Description
--------- | ------- | -----------
passphrase | string | no help info
pin | string | no help info
showprivkey | string | no help info

## method: keypair

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"keypair\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/keypair
```

field | value type | Description
--------- | ------- | -----------

## method: priv2pub

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"priv2pub\",\"privkey\":\"{hash}\",\"addrtype\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/priv2pub?privkey={hash}&addrtype={int}
```

field | value type | Description
--------- | ------- | -----------
privkey | hash | no help info
addrtype | int | no help info

## method: wif2priv

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"wif2priv\",\"wif\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/wif2priv?wif={string}
```

field | value type | Description
--------- | ------- | -----------
wif | string | no help info

## method: priv2wif

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"priv2wif\",\"priv\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/priv2wif?priv={string}
```

field | value type | Description
--------- | ------- | -----------
priv | string | no help info

## method: addr2rmd160

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"addr2rmd160\",\"address\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/addr2rmd160?address={string}
```

field | value type | Description
--------- | ------- | -----------
address | string | no help info

## method: rmd160conv

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"rmd160conv\",\"rmd160\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/rmd160conv?rmd160={string}
```

field | value type | Description
--------- | ------- | -----------
rmd160 | string | no help info

## method: cipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"cipher\",\"privkey\":\"{hash}\",\"destpubkey\":\"{hash}\",\"message\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/cipher?privkey={hash}&destpubkey={hash}&message={str}
```

field | value type | Description
--------- | ------- | -----------
privkey | hash | no help info
destpubkey | hash | no help info
message | str | no help info

## method: decipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"decipher\",\"privkey\":\"{hash}\",\"srcpubkey\":\"{hash}\",\"cipherstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/decipher?privkey={hash}&srcpubkey={hash}&cipherstr={str}
```

field | value type | Description
--------- | ------- | -----------
privkey | hash | no help info
srcpubkey | hash | no help info
cipherstr | str | no help info

## method: broadcastcipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"broadcastcipher\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/broadcastcipher?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: broadcastdecipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"broadcastdecipher\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/broadcastdecipher?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: multicastcipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"multicastcipher\",\"pubkey\":\"{hash}\",\"message\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/multicastcipher?pubkey={hash}&message={str}
```

field | value type | Description
--------- | ------- | -----------
pubkey | hash | no help info
message | str | no help info

## method: multicastdecipher

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"SuperNET\",\"method\":\"multicastdecipher\",\"privkey\":\"{hash}\",\"cipherstr\":\"{str}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/SuperNET/multicastdecipher?privkey={hash}&cipherstr={str}
```

field | value type | Description
--------- | ------- | -----------
privkey | hash | no help info
cipherstr | str | no help info

mouse API
===
need to create help/mouse.md file

## method: image

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"mouse\",\"method\":\"image\",\"name\":\"{string}\",\"x\":\"{int}\",\"y\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/mouse/image?name={string}&x={int}&y={int}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info
x | int | no help info
y | int | no help info

## method: change

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"mouse\",\"method\":\"change\",\"name\":\"{string}\",\"x\":\"{int}\",\"y\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/mouse/change?name={string}&x={int}&y={int}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info
x | int | no help info
y | int | no help info

## method: click

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"mouse\",\"method\":\"click\",\"name\":\"{string}\",\"x\":\"{int}\",\"y\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/mouse/click?name={string}&x={int}&y={int}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info
x | int | no help info
y | int | no help info

## method: close

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"mouse\",\"method\":\"close\",\"name\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/mouse/close?name={string}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info

## method: leave

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"mouse\",\"method\":\"leave\",\"name\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/mouse/leave?name={string}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info

keyboard API
===
need to create help/keyboard.md file

## method: key

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"keyboard\",\"method\":\"key\",\"name\":\"{string}\",\"c\":\"{int}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/keyboard/key?name={string}&c={int}
```

field | value type | Description
--------- | ------- | -----------
name | string | no help info
c | int | no help info

hash API
===
need to create help/hash.md file

## method: hex

This API call is used to convert any input string to hexadecimal value. Converting a string to hexadecimal provides a single long alphanumerical string.

The example shows if we convert a small example of HTML code to hexadecimal using API call what it would look like:

> Example string (HTML Code):

```text
<html><head><title>Home Page</title></head><body><h1>Hello World</h1><p>This is test.</p></body></html>
```

> HTTP API call example for converting to hexadecimal:

```text
http://127.0.0.1:7778/api/hash/hex?message=<html><head><title>Home+Page</title></head><body><h1>Hello+World</h1><p>This+is+test.</p></body></html>
```

> End result:

```text
{
  "result": "hash calculated",
  "message": "<html><head><title>Home Page</title></head><body><h1>Hello World</h1><p>This is test.</p></body></html>",
  "hex": "3c68746d6c3e3c686561643e3c7469746c653e486f6d6520506167653c2f7469746c653e3c2f686561643e3c626f64793e3c68313e48656c6c6f20576f726c643c2f68313e3c703e5468697320697320746573742e3c2f703e3c2f626f64793e3c2f68746d6c3e00",
  "tag": "7729339918800585698"
}
```



> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"hex\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/hex?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: unhex

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"unhex\",\"hexmsg\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/unhex?hexmsg={string}
```

field | value type | Description
--------- | ------- | -----------
hexmsg | string | no help info

## method: curve25519_pair

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"curve25519_pair\",\"element\":\"{hash}\",\"scalar\":\"{hash}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/curve25519_pair?element={hash}&scalar={hash}
```

field | value type | Description
--------- | ------- | -----------
element | hash | no help info
scalar | hash | no help info

## method: NXT

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"NXT\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/NXT?passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
passphrase | string | no help info

## method: curve25519

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"curve25519\",\"pubkey\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/curve25519?pubkey={string}
```

field | value type | Description
--------- | ------- | -----------
pubkey | string | no help info

## method: crc32

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"crc32\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/crc32?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: base64_encode

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"base64_encode\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/base64_encode?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: base64_decode

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"base64_decode\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/base64_decode?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: rmd160_sha256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"rmd160_sha256\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/rmd160_sha256?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha256_sha256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha256_sha256\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha256_sha256?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha224

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha224\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha224?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha256\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha256?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha384

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha384\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha384?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha512

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha512\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha512?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: rmd128

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"rmd128\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/rmd128?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: rmd160

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"rmd160\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/rmd160?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: rmd256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"rmd256\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/rmd256?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: rmd320

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"rmd320\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/rmd320?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: sha1

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"sha1\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/sha1?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: md2

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"md2\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/md2?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: md4

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"md4\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/md4?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: md5

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"md5\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/md5?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: tiger192_3

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"tiger192_3\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/tiger192_3?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

## method: whirlpool

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hash\",\"method\":\"whirlpool\",\"message\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hash/whirlpool?message={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info

hmac API
===
need to create help/hmac.md file

## method: sha224

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"sha224\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/sha224?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: sha256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"sha256\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/sha256?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: sha384

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"sha384\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/sha384?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: sha512

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"sha512\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/sha512?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: rmd128

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"rmd128\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/rmd128?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: rmd160

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"rmd160\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/rmd160?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: rmd256

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"rmd256\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/rmd256?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: rmd320

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"rmd320\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/rmd320?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: sha1

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"sha1\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/sha1?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: md2

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"md2\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/md2?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: md4

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"md4\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/md4?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: md5

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"md5\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/md5?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: tiger192_3

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"tiger192_3\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/tiger192_3?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

## method: whirlpool

put helpful info here


> Shell command format:

```shell
curl --url "http://127.0.0.1:7778" --data "{\"agent\":\"hmac\",\"method\":\"whirlpool\",\"message\":\"{string}\",\"passphrase\":\"{string}\"}"
```

> HTTP API call format:

```url
http://127.0.0.1:7778/api/hmac/whirlpool?message={string}&passphrase={string}
```

field | value type | Description
--------- | ------- | -----------
message | string | no help info
passphrase | string | no help info

end of help

