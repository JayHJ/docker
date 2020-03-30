# docker
-- docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=123456 -d mysql --lower_case_table_names=1
-- docker run -p 6379:6379 --name redis -v /Users/redis/data:/data -d redis redis-server --appendonly yes
-- docker run -p 27017:27017 --name mongo -v /Users/jay/Documents/tools/mongo/data:/data/db -e MONGO_INITDB_ROOT_USERNAME=root -e MONGO_INITDB_ROOT_PASSWORD=123456 -d mongo
