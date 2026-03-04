psql -U postgres
CREATE DATABASE lb1;
psql -U postgres -d lb1 -f lab1_dump.sql
