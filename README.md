# CRUD-app-with-JSON-file
Curl Commands to fetch the data

==================================================================================================================
==========================
List Account
==========================
**Request**
curl --location 'http://localhost:3000/account/list'

**Response:**
{
    "1465": {
        "username": "madfinger11",
        "email": "maddy@gmail.com",
        "password": "yddam5342"
    },
    "2646": {
        "username": "yemiakin",
        "email": "emiakiy@gmail.com",
        "password": "iy@g65"
    },
    "3253": {
        "username": "ikechifortune",
        "email": "echifo@gmail.com",
        "password": "ifo#mf23"
    }
}

==================================================================================================================
==========================
Add Account
==========================
**Request**

curl --location 'http://localhost:3000/account/addaccount' \
--header 'Content-Type: text/plain' \
--data-raw '{
        "username": "sri",
        "email": "cloud.share360@gmail.com",
        "password": "Sairam3333"
}'

**Response:**

{
    "success": true,
    "msg": "account data added successfully"
}


