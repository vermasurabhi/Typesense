# Typesense
Typesense commands to work locally

## Install typesense with docker
>> docker pull typesense/typesense:26.0

## Run Typesense docker
>> docker run -p 8108:8108 -v %cd%\typesense-data:/data typesense/typesense:26.0 --data-dir /data --api-key=xyz --enable-cors

## Open postman and hit
GET http://localhost:8108/health
Header key- X-TYPESENSE-API-KEY value- xyz

it should give 
{
    "ok": true
}

## making a collection


