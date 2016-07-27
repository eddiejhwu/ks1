readme.ks1.txt
-------------------------------------------------------------------------------
ks1: project ks1 (first keystone project) using keystone
-------------------------------------------------------------------------------
by eddie, 2016/6/24

have to startup mongodb first, otherwise you'll got error

start mongodb: (and specify corresponding dbpath)
C:\"Program Files"\MongoDB\Server\3.2\bin\mongod --dbpath d:\nws\db

start ks1:
node keystone
or
npm start

on browser
http://localhost:3000/

a default Admin user with the email eddie.wu@maa.com.tw and the password c5c5123.


-------------------------------------------------------------------------------
config
-------------------------------------------------------------------------------
in file .env
update cloudinary and mandrill email settings to eddie's account
CLOUDINARY_URL=cloudinary://411832653252624:NR9BVBw91_aXdeVDBoNWghBWeVw@dlmiguvji
MANDRILL_API_KEY=3a6bd80a4ef196a7be218d5bce43c494-us13


-------------------------------------------------------------------------------
ref
-------------------------------------------------------------------------------
keystone:
	http://keystonejs.com/
	http://keystonejs.com/docs/getting-started/
	https://twitter.com/keystonejs
express:
	http://expressjs.com/
	http://expressjs.com/en/api.html
jade / pug: (jade has renamed to pug)
	https://github.com/pugjs/pug
	http://jade-lang.com/api/
	http://jade-lang.com/tutorial/

fancybox: (add fancybox to gallery.jade)
	http://fancyapps.com/fancybox/


-------------------------------------------------------------------------------
ebooks
-------------------------------------------------------------------------------
Practical Keystone.js:
	https://leanpub.com/keystonejs/read#leanpub-auto-what-are-web-frameworks



-------------------------------------------------------------------------------
sites using keystone
-------------------------------------------------------------------------------
http://www.savethefood.com/


