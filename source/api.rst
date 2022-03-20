.. AkkeyAPIDocs documentation master file, created by
   sphinx-quickstart on Sun Mar 20 14:09:00 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

========
Base URL
========
基本URL: https://akkey57492.ml/api/v1

=======
Discord
=======
Discordに関するAPIです。

Base URL(Discord)
=================
基本URL: https://akkey57492.ml/api/v1/discord

GET scamurl > (List)Scam urls / (String)Scam url
================================================

説明
----
scamurlの一覧、または存在するかを確認できます。

利用可能Header
-------------
- 無し

必要Data
--------
- 無し

利用可能Json
-----------
- 無し

利用可能パラメーター
- get(特定のリンクがあるかを探します)

POST scamurl > (Bool)result
===========================

説明
----
Discordのscamurlを追加します。(申請できます)

利用可能Header
-------------
- 無し

必要Data
--------
- 無し

利用可能Json
-----------
- 無し

利用可能パラメーター
------------------
- url(scamのURLを入力できます。)
