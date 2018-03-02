## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The value attribute of the <input> element in the html form.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
We have not defined a GET route for '/teachers'

3. What type of request did your browser just perform?
GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
Because we defined a POST route to go to '/teachers' when we create a teacher. 