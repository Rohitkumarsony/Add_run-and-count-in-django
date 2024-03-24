# Add_run-and-count-in-django
#in this project how to run add on our site from youtube or localvideo
#using ajax and count user how many times see add based on id and date
#using     user_ip=request.META.get('HTTP_X_FORWARED_FOR') for tracker user_ip
#used geopy for finding location
#using django authenticate function for login

#if user upload image it will automatically deduct and show on the screen
#if user upload video it will deduct and show with one input tag
using ajax for finding user ip if user using proxy then it will deduct by request.META.get('HTTP_X_FORWARED_FOR')
this method

other wise it will show by this method          ip=request.META.get('REMOTE_ADDR')

#managing video count and image count only with one ajax
