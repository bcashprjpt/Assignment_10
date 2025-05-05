# Assignment_10
#
# @ setting.py
# * Here we have placed blog app under install app and also added static MEDIA_ROOT and MEDIA_URL
# 
# @ template.py
# post.html:
  * Here we have use for loop in the html page to get the post, posted by the admin
	* Here I have placed title, publish_date, image and summary
	* and place a link on title which redirect to the detail.html page
# detail.html:
   * Here we have shown the detail of the blog by showing the title,publish_date,image and body

# @ admin.py:
	* Here we have register a model blog
	
# @ model.py:
	* Here we have created Post class and assign a title field, publish_date, image and body
	* Here we have use summery() method to return the first 100 char from the body
	* Here we have use pub_date() method to return the publish_date in MMM DD, yyyy formate
	* Here we have use __str__() method to return the titleof the blog

# @ views.py:
	* Here we have use allpost() method to render the post object into post.html page
	* Here we have use detail() method to render by passing blog_id as argument and return detail to  the detail.html page
	
	
	
