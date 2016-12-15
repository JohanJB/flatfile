#Les boucles #

## Code ##

  {{% for page. in site.pages  %}}
        
         {{ page.title }}
        
        {% end for %}


ou


 {% for post in site.posts %}
           
   
  
    {{ post.content }}
  
  {% endfor %}