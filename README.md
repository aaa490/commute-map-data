# 記録用の地図のマス

通勤の走行記録を地図に重ねるための、車の道と店の形の小さなデータです（約10km四方のマスごとの SQLite を gzip）。
置いているのは OpenStreetMap から抜いた物だけで、走行の記録や個人の情報は入っていません。

- 一覧：`index/index.json`（版・マスごとの大きさと置いたフォルダ）
- マス：`masu-<版>-<n>/m_<マスの鍵>.db.gz`

## 出典・ライセンス

Map data © OpenStreetMap contributors, available under the Open Database License (ODbL) 1.0.
https://www.openstreetmap.org/copyright ・ https://opendatacommons.org/licenses/odbl/1-0/
出典：OpenStreetMap（Geofabrik の日本の抜き出し）: way[highway~"motorway|motorway_link|trunk|trunk_link|primary|primary_link|secondary|secondary_link|tertiary|tertiary_link|unclassified|residential|living_street|service"]・shop=*・amenity=fuel（版 2026-10-16）

このデータは ODbL 1.0 に従い、同じ条件で誰でも使えます。
