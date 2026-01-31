mysql> use hotel_db;
Database changed
mysql> select * from hotel_db;
ERROR 1146 (42S02): Table 'hotel_db.hotel_db' doesn't exist
mysql> select * from reservation;
ERROR 1146 (42S02): Table 'hotel_db.reservation' doesn't exist
mysql> show tables;
+--------------------+
| Tables_in_hotel_db |
+--------------------+
| reservations       |
+--------------------+
1 row in set (0.04 sec)

mysql> select * from reservations;
+----------------+------------+-------------+---------+---------------------+----------------+
| reservation_id | guest_name | contact_no  | room_no | check_in_time       | check_out_time |
+----------------+------------+-------------+---------+---------------------+----------------+
|              1 | pramit     | patel       |     217 | 2026-01-31 15:07:19 | NULL           |
|              2 | ram        | 52564122514 |      45 | 2026-01-31 15:30:20 | NULL           |
+----------------+------------+-------------+---------+---------------------+----------------+
2 rows in set (0.00 sec)

mysql>
