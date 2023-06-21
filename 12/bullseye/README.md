select * from pg_settings where name ='wal_level';
SELECT current_setting('shared_preload_libraries');
create extension pglogical;
