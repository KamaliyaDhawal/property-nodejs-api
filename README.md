# Property

# git clone https://github.com/KamaliyaDhawal/property-nodejs-api.git
# cd ./property-nodejs-api
# npm install
# set .env
# import db_dump
# npm start
# postman link: https://www.getpostman.com/collections/ba5e43d8054b92ea8b53

# Note:
    - In-case If you get DB Error "GROUP BY clause and contains nonaggregated column" means you need to set sql_mode as ONLY_FULL_GROUP_BY
    - In-case If you get error like Unexpected end of JSON input means there are long data comming in our gourp by query need to set group_concat_max_len
    MEDIA_PATH={YOUR_SERVER_WITH_PORT}/api/{ROUTE}/getImages (http://localhost:3000/api/property/getImages)