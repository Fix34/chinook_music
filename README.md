# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
Réponses aux questions : 
A)
1) Track.count = 347
2) u = Track.find_by(title: 'White Room') => Eric Clapton
3) u = Track.find_by(duration: '188133') => Perfect
4) u = Album.find_by(title: 'Use Your Illusion II') => Guns n Roses
B)
1) Topic.where("name like ?",'%apple%').count => 13
2)
3) Album.where(artist: "AC/DC").count => 2
4) Track.where(duration: 158589).count => 0
C)
