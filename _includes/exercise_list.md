{% assign exercise_category = site.data.exercises | group_by: "category" %}

{% for category in exercise_category %}1. {{[category.name}}
{% for exercise in category.items %}   - [{{exercise.name}}]({{relative-baseurl}}{{exercise.base_url}}{{exercise.teacher_page}})
{% endfor %} {% endfor %}
