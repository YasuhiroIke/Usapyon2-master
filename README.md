# Usapyon2-master

「うさぴょん２」ではクラスタ並列化構成を予定しているのですが、その内のマスター側部分になります。

<strike>元にしているソフトは基本的にありません。</strike>

<strike>USI系の処理が色々と必要なので、結局「なのはmini」や「StockFish7」から持って来る事になりました…。</strike>

基本的には通信部だけを実装しています。USI-slaveとUSI-masterに分かれています。

USI-masterでは、３台構成を前提に諸々ハードコーディングしていますが、改造すれば台数とかもっと増やせるかも？

Usapyon2-Slave（もしくはそれに類するモノ）がないと、探索部分がどこにもないので、動きません。

<strike>また、Usapyon2-Slaveは特殊なオプションを付けて実行する必要があります。</strike>

「なのはmini」の作者、川端一之様、「Apery」の作者、平岡拓也様、 「StockFish」の作者、Tord Romstad様、Marco Costalba様, Joona Kiiski様,Gary Linscott様に深く感謝をしております。

Usapyon2, a USI shogi(japanese-chess) playing engine

Copyright (C) 2015-2016 Yasuhiro Ike

Usapyon2 is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Usapyon2 is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
