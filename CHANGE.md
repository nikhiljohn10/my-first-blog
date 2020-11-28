CHANGES
-------

- .gitignore
	- change `static/` to `/static`

- Add truncate text to blog post list
	- `{{ post.text|linebreaksbr|truncatechars:77 }}`

- Change edit button size in post_detail.html
	- `<a class="btn btn-default btn-sm" href="{% url 'post_edit' pk=post.pk %}">`

- Update html tags to Semantic tags
