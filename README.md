# Flipkartt

# TABLE:Online book portal
|s_no||Categeory   ||Popularity ||Price||newest_first|
|----||------------||-----------||-----||------------|
| 1  ||COMIC STORY ||   4       || 450 || 19\08\2017 |
| 2  |G|OVT EXAM   ||   3       ||678  || 16\09\2019 |
| 3  ||NOVELS      ||   2       || 980 || 30\05\2015 |

## PRICE LOW-HIGH
select s_no,Categeory,Popularity,Price,newest_first from book order by Price ASC;

## POPULARITY HIGH-LOW
select s_no,Categeory,Popularity,Price,newest_first from book order by Popularity DESC;

## NEWEST FRIST NEW-OLD
select s_no,Categeory,Popularity,Price,newest_first from book order by Newest first DESC;
