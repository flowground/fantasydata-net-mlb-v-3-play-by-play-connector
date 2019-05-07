# ![LOGO](logo.png) MLB v3 Play-by-Play **flow**ground Connector

## Description

A generated **flow**ground connector for the MLB v3 Play-by-Play API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/mlb-v3-play-by-play/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:31+03:00

## API Description

MLB play-by-play API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Play By Play

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `gameid` - _required_ - The GameID of an MLB game.  GameIDs can be found in the Games API.  Valid entries are <code>14620</code> or <code>16905</code>

### Play By Play Delta

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.
* `minutes` - _required_ - Only returns plays that have changed in the last X minutes.  You specify how many minutes in time to go back.  Valid entries are:
<code>1</code>, <code>2</code> ... <code>all</code>.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-mlb-v-3-play-by-play-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
