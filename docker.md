# DOCKER
1. mysql v5.7 not valid
  -> SHOULD use `FROM mysql:5.7.24`
2. auto init dabase: mapping folder initdb to `/docker-entrypoint-initdb.d`
  -> MUST delete data folder(if exist) 
