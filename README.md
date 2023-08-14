# COVID-19_Tracking_App
# about project
for getting data inside app - use api's
2 api's : 1- data across the world
          2. data in india along with states

for fetching data from this api's use volley library: for handling & retriving data.
it is open source authebticate api & its updated in every 10 min
added dependency in build.gradle file
manifestfile- internet permission-getting data from net
create void fetchdata() method : to fetch data from third party api and implent into app
create stribg req. using volley & assign url= "https://corona.lmao.ninja.com"
requested data are in JSON format
inside onResponse method create object of JSONobject class
set data in textview which is available in JSON format.


# volley library:
is a http library that makes networking for andoid apps easier faster
volley offers: automatic scheduling of network requests.


![WhatsApp Image 2022-06-23 at 12 33 50 PM](https://user-images.githubusercontent.com/91388114/175236753-a803d435-6805-4bf0-9e8f-2aaf13f6dbe9.jpeg)
![WhatsApp Image 2022-06-23 at 12 33 51 PM](https://user-images.githubusercontent.com/91388114/175236759-ff8baf67-bebd-49af-aaac-dd7c72aac092.jpeg)
![WhatsApp Image 2022-06-23 at 12 33 52 PM](https://user-images.githubusercontent.com/91388114/175236766-0cd71e4d-319a-4538-a959-ca99e163c392.jpeg)
![WhatsApp Image 2022-06-23 at 12 33 51 PM (1)](https://user-images.githubusercontent.com/91388114/175236769-f97000ba-34c4-409f-95d4-d2d2349dff8e.jpeg)
