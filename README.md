PhD FBK students
====================
based on Agency theme  [Agency bootstrap theme ](http://startbootstrap.com/templates/agency/)

# How to use

###Students

All the students profiles are in 'students/_posts'

Images are in '/img/students'

images size must be 150x150
for each student two images must be provided: surname.jpg and surname_thumb.jpg

it is possible to generate the list of users starting from a csv file called students.csv, using the csv2jekyll-students.py
script:
py csv2jekyll-students.py

an example of students.csv is provided in students/_posts/students.csv

the first column is autogenerated and it will be the student file name
image, thumbnail,alt and modal-id are auto generated





###Alumni

All the students profiles are in 'alumni/_posts'

Images are in '/img/alumni/'


##Open Calls
All calls are in 'opencalls/_posts'

Calls are organized by university:
there are the University files  that must contain the 
tag "call_uni"
and a subtag that identify the calls

for example for the University of Trento
tag: call_uni  (it is used to list all the university)
subtag: uni_trento_call  (the tag of the calls)

in each university call there must be the tag corrisponding to the subtag of the university
example:

tag: uni_trento_call
###Network

  all the files are in affiliations/_posts
  images in img/affiliation

  the tag: network is mandatory
  for each university there could be more than one department.
  the field 'department' contains the tag that identify the dipartments
    department: unipd_department
  the field 'modal-id' is mandatory and must be unique
  
###About

Images are in '/img/about/'



=========
For more details, read [documentation](http://jekyllrb.com/)
