Steps To Run Program

1.Download Folder From Git.

2.Run - composer install

3.Create database as 'recruitment ' and change .env file.

3.Run - php artisan migrate



For API End point is:

Register:
end point :   /save
name::akash
email:akash@gmail.com
password:welcome


Login:
end point :   /login
email:akash@gmail.com
password:welcome

Generates Token which can be used to get Candidates List.This token can be passed in Authorization header.

Create Candidate :POST /v1/candidates

Find Candidate By ID :GET /v1/candidates/:id

List Candidates :GET /v1/candidates

Search Candidates :GET /v1/candidates/search