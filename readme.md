create table lds_features(datum datetime); // datetime wichtig für data adapter, für bool muss 'boolean' ausgewählt werden, damit das erkannt wird

select date('now')

insert into lds_features values('2018-10-11');

select strftime('%d.%m.%Y') from lds_features;