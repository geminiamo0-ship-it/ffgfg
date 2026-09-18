# NBME 34 Database Status

Generated from commit: `e69e9700b933dfe53de38911cdc7e9406c7af29d`

## SQLite integrity
```text
ok
```

## Tables
```text
options  questions  sqlite_sequence
```

## Counts

- Questions: 40
- Options: 214

## Latest IDs

- Max question id: 40
- Max uworld_id: 40
- Max option id: 219

## Latest question rows
```text
id  uworld_id  subject  system  topic  source    created_at              
--  ---------  -------  ------  -----  --------  ------------------------
40  40                                 nbme-pdf  2026-09-18T02:17:34.708Z
39  39                                 nbme-pdf  2026-09-18T02:14:03.145Z
38  38                                 nbme-pdf  2026-09-18T02:11:23.498Z
37  37                                 NBME 34   2026-09-18T05:00:51     
36  36                                 NBME 34   2026-09-18T04:42:38     
35  35                                 NBME 34   2026-09-18T04:40:41     
34  34                                 NBME 34   2026-09-18T04:37:20     
33  33                                 NBME 34   2026-09-18T04:35:22     
32  32                                 NBME 34   2026-09-18T04:34:49     
31  31                                 NBME 34   2026-09-18T04:34:19     
```

## Question columns
```text
0 | id | INTEGER | 0 | None | 1
1 | uworld_id | INTEGER | 0 | None | 0
2 | text_html | TEXT | 0 | None | 0
3 | explanation_html | TEXT | 0 | None | 0
4 | subject | TEXT | 0 | None | 0
5 | system | TEXT | 0 | None | 0
6 | topic | TEXT | 0 | None | 0
7 | source | TEXT | 0 | None | 0
8 | created_at | TEXT | 0 | None | 0
```

## Option columns
```text
0 | id | INTEGER | 0 | None | 1
1 | question_id | INTEGER | 0 | None | 0
2 | text_html | TEXT | 0 | None | 0
3 | is_correct | BOOLEAN | 0 | None | 0
4 | option_order | INTEGER | 0 | None | 0
5 | uworld_chosen_by | INTEGER | 0 | None | 0
6 | choice_api_id | TEXT | 0 | None | 0
```
